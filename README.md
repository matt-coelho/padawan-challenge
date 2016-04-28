###Descrição da vaga
Acesse: https://gist.github.com/andreybleme/9f30727c63cd92cd08993873c55a60fd

###Introdução

Uma empresa deseja criar um sistema para calcular a folha de pagamento mensal.

####Requisitos Funcionais:

**RF1.** Armazenar os dados dos funcionários (matricula, nome, cargo, cpf, endereço e e-mail de contato), o seu salário bruto, o valor mensal do vale alimentação e transporte.

**RF2.** O sistema precisa calcular os salários líquidos dos funcionários considerando que o salário líquido de cada funcionário é calculado por:
> *salario liquido = salario bruto + transporte + alimentação*

**RF3.** Armazenar os dados dos funcionários de campo (matricula, cargo, nome, cpf, endereço e e-mail de contato), o seu salário bruto, o valor mensal do vale alimentação e transporte e o valor do adicional mensal por periculosidade.

**RF4.** O sistema precisa calcular os salários líquidos dos funcionários de campo considerando que o salário líquido de cada funcionário de campo é calculado por:
> *salario liquido = salario bruto + transporte + alimentação + adicional*

**RF5.** Armazenar os dados dos funcionários de diretoria (matricula, nome, cargo, cpf, endereço e e-mail de contato), o seu salário bruto e o percentual sobre o lucro mensal da empresa.

**RF6.** O sistema precisa calcular os salários líquidos dos diretores. Neste caso, cada diretor recebe um percentual sobre o lucro da empresa no mês. Dessa forma:
> *salario liquido = salario bruto + lucro mensal ∗ percentual*

**RF7.** Armazenar os dados dos representantes comerciais da empresa (matricula, nome, cargo, cpf, endereço e e-mail de contato) e o valor percentual da comissão e a ajuda de custo mensal.

**RF8.** O sistema precisa calcular os vencimentos dos representantes comerciais considerando que o salário líquido de cada funcionário é calculado por:
> *salario liquido = salario bruto + gratificação mensal*

**RF9.** O sistema precisa calcular a folha de pagamento completa de todos os funcionários cadastrados no sistema.

###Regras de Negócio:

**RN1.** Caso os funcionários, funcionários de campo e diretores tiverem alguma falta durante o mês a quantidade de dias faltados devem ser debitados:

> *salario liquido = salario liquido − (salario bruto / 30) * quantidades de faltas no mes*

**RN2.** Um funcionário não pode ter a quantidade de faltas maior que 30 dias trabalhados no mês.

**RN3.** Caso funcionários e funcionários de campo trabalhem horas extras estas horas devem ser acrescidas de acordo com o seguinte cálculo:

> *salario liquido = salario liquido + quantidade de horas extras ∗ (salario bruto / 200 )*
