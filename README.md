# ModelTestPlan-QA
Planejamento para criação de cenários de testes que garatam cobertura em aplicação em funcionalidade de cadastro - aplicação web

1.	Funcionalidade – Cadastro

Comportamento esperado 
•	 ao digitar o nome, e-mail, senha, repetir senha um cadastro será realizado na plataforma
•	Um botão “cadastrar” deve ser habilitado para o usuário
•	Usuário deve ser redirecionado para a tela de login
•	A plataforma deve indicar campos obrigatórios a serem corrigidos pelo usuário

Verificações

•	Senha [mínimo 4 caracteres]
•	O campo nome deve conter [50 caracteres no máximo, sem número ou caracteres especiais];
•	O campo “repetir senha” deve ser igual ao campo “senha” 
•	O e-mail cadastrado deve estar no formato nome@email.algo

Critérios de aceite

•	Os campos devem ser validados logo após a saída
•	O sistema deve funcionar em todos os navegadores
•	Todos os campos devem ser obrigatórios
•	Exibir mensagem de confirmação em cada positivo
•	Redirecionar o usuário para a tela de login
•	Exibir mensagem de falha em caso e-mail já existente
•	Exibir mensagem de falha em caso de senha não correspondente
•	Exibir mensagem de falha de campo obrigatório incompleto
•	Uma mensagem de “cadastro realizado com sucesso” deverá ser exibida pela plataforma.






● Escopo de Testes

Serão executados testes em todos os níveis conforme a descrição abaixo.

Testes Unitários: o código terá uma cobertura de 60% de testes unitários, que são
de responsabilidade dos desenvolvedores.

Testes de Integração: Serão executados testes de integração em todos os
endpoints, e esses testes serão de responsabilidade do time de qualidade.

Testes Automatizados: Serão realizados testes end-to-end na funcionalidade de
Login.

Testes Manuais: a funcionalidade deverá ser testada manualmente pelo time
de qualidade seguindo a documentação de Cenários de teste e destes TestPlan.
