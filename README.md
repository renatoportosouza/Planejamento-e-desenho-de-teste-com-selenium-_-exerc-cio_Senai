Plano de Teste
Plano de Testes Funcional para o Sistema Projeto-API com Selenium

Objetivo: Este plano de testes tem como objetivo definir as estratégias, processos e recursos necessários para a realização de testes funcionais no sistema Projeto-API.

Escopo: O escopo deste plano de testes inclui a verificação de todas as funcionalidades (Inserir, Excluir e Editar) do sistema Projeto-API.

Processo de Teste:
1. Preparação do Ambiente de Teste 

Pré-condições: 
a.	O Node.js encontrado no link https://nodejs.org/en/download/ deve ser instalado no computador;
b.	Os servidores http-server e json-server devem ser instalados e executando dentro do Node na máquina corretamente;
c.	O sistema Projeto-API deve estar disponível localmente;
d.	Navegador Google Chrome com o Pluggin do Selenium IDE instalado no navegador.


2. Execução dos Casos de Teste


Ferramentas de Teste:   Selenium IDE e Google Chrome.


Nome: Renato Pôrto Souza
	Data início:   30/01/2025	Data de Conclusão: 30/01/2025


1 Preparação de Ambiente


Tipos de Teste:
- Teste de Integração [X] - Teste Funcional [X] –Teste de Unidade [  ] - Teste de Sistema [  ] - Teste de Aceitação [  ]

Ambiente de Teste:

Sistema Operacional	Windows 10 Home Single Language
Configuração	Intel(R) Core(TM) i5-7200U CPU @ 2.50GHz   2.71 GHz / HD 1 TB / SSD 20,0 GB / Sistema operacional de 64 bits, processador baseado em x64
Banco de Dados	Json-Server
Servidor de Aplicação	HTTP-SERVER
Versão do Sistema	Projeto API - V1.0



Equipe de Teste:
- Execução de Teste: Renato Pôrto Souza
- Líder de Teste:  Renato Pôrto Souza
- Engenheiro de Teste 1: Tutor Senai


Aprovação:
- Aprovação do Líder de Teste: Renato Pôrto Souza
- Aprovação do Gerente de Projeto: Tutor SENAI





2. Execução dos Casos de Teste
Caso de Teste: Inserir

ID do Caso de Teste: TC-001 - Inserir

Propósito: Inserir UM cadastro de cliente com nome e endereço no Projeto-API executando de servidor local através do Selenium IDE.

Preparação:
-No Google Chrome entrar na extensão Selenium IDE e abrir o link gerado pelo http-server para o Projeto-API. Deverá criar o arquivo Inserir.side com a gravação do procedimento de Inserir do Projeto-API. Após gerar este arquivo testar pelo menos três vezes e observar o comportamento funcional do sistema através do teste automático.

Resultado Esperado:
- O resultado esperado é que a cada vez que execute o Inserir.side seja gravado um cadastro com nome e endereço no Projeto-API, criando o cadastro com um novo ID o projeto.


Relatório de Defeitos:
Sem erros


Teste Aprovado [X] - Teste Reprovado [  ]
Data de Início: 30/01/2025 23:13 - Data de Conclusão: 30/01/2025  23:13







Caso de Teste: Excluir

ID do Caso de Teste: TC-002 - Excluir

Propósito: Excluir UM cadastro do cliente no Projeto-API executando de servidor local através do Selenium IDE.

Preparação:
-No Google Chrome entrar na extensão Selenium IDE e abrir o link gerado pelo http-server para o Projeto-API. Deverá criar o arquivo Excluir.side com a gravação do procedimento de Exclusão do Projeto-API. Após gerar este arquivo testar pelo menos duas vezes e observar o comportamento funcional do sistema através do teste automático.

Resultado Esperado:
- O resultado esperado é que a cada vez que execute o Excluir.side seja retirado um cadastro do Projeto-API.


Relatório de Defeitos:
Sem erros

Teste Aprovado [X] - Teste Reprovado [  ]
Data de Início: 30/01/2025 23:20 - Data de Conclusão: 30/01/2025 23:24










Caso de Teste: Editar

ID do Caso de Teste: TC-003 - Editar

Propósito: Editar O cadastro de cliente com o nome fwefwefwe e endereço sSa no Projeto-API executando de servidor local através do Selenium IDE.

Preparação:
-No Google Chrome entrar na extensão Selenium IDE e abrir o link gerado pelo http-server para o Projeto-API. Deverá criar o arquivo Editar.side com a gravação do procedimento de edição do Projeto-API. Após gerar este arquivo testar pelo menos uma vez e observar o comportamento funcional do sistema através do teste automático.

Resultado Esperado:
- O resultado esperado é que a cada vez que execute o Editar.side seja editar um cadastro do Projeto-API.


Relatório de Defeitos:

Sem erros



Teste Aprovado [X] - Teste Reprovado [  ]
Data de Início: 30/01/2025 23:30 -Data de Conclusão: 30/01/2025 23:30
