# 🌟  Desenvolvimento de um software em linguagem C 

O software destina-se ao gerenciamento eficiente e seguro do cadastro, 
consulta e análise de dados de empresas que trabalham na redução de resíduos
industriais. Ele oferece funcionalidades como autenticação de funcionários, 
geração de relatórios e medidas de segurança, como mascaramento de dados sensíveis
(CPF e CNPJ), utilizando uma arquitetura modular.

## 🌟 Descrição do Sistema

- Objetivo: Criar um sistema que gerencie cadastros de empresas e relatórios ambientais.
- Funcionalidades Principais:
- ✅Cadastrar Empresas: Registro de dados como CNPJ, endereço e nome do responsável.
- 🔍Consultar Empresas: Permite buscar e visualizar informações cadastradas.
- 📊Visualizar Relatórios: Geração de relatórios por região ou empresa.
- 💾Gerenciamento: Atualização de dados, exportação em CSV/TXT.

## 🌟 Arquitetura do Sistema
- Modularidade: Divisão em módulos para flexibilidade e escalabilidade.
- Módulos Principais:
- - Autenticação: Login seguro com senha oculta.
  - Cadastro: Registro de empresas com mascaramento de CPF e CNPJ.
  - Relatórios: Geração e exportação de dados.
  - Gerenciamento: Atualização de informações globais e individuais.
 
 ## 🌟 Manual de Instalação
- Requisitos:
- -IDE recomendada: Code::Blocks.
- Compilador: GCC via MinGW.
- Passos de Instalação:
- Baixe e descompacte o código.
- Compile utilizando o GCC.
- Execute o programa gerado no terminal ou IDE.

## Planilha de Testes
![image](https://github.com/user-attachments/assets/61165d7d-9278-47fe-bc42-a209a7078dbe)

## Diagramas
- Caso de Uso:
Este diagrama de caso de uso apresenta as principais funcionalidades de um sistema 
de gestão, acessíveis ao ator "Funcionário". As elipses representam as ações que o 
funcionário pode realizar: ![image](https://github.com/user-attachments/assets/2591043c-c1bd-49ed-89d4-12f0b889124e)

- Diagrama de Atividade:
Este tipo de diagrama é particularmente útil para modelar a lógica de negócios, 
descrever o funcionamento interno de um sistema, ou detalhar uma sequência de 
tarefas em um processo. No exemplo a seguir, apresentamos um Diagrama de Atividade da tela onde o usuário 
faz o login: ![image](https://github.com/user-attachments/assets/8cfd2e83-e4d1-4ec5-bf7f-a2c8a27d2064)

## Manual do Usuário:
- Login inicial: **Usuário: UNIP | Senha: 2024.**
- Funcionalidades do Menu:
- - Cadastro e consulta de empresas.
  - Visualização de relatórios residuais.
  - Gerenciamento global e por empresa.
  - Cadastro de funcionários acessrem o sistema.

## Possíveis Melhorias Futuras
- Acessibilidade pela internet: Implementar uma interface web com banco de dados online.
- Relatórios em tempo real: Integrar com ferramentas como Power BI.
- Segurança avançada: Implementar autenticação multifatorial e criptografia.

## Estrutura de Arquivos
- Dados armazenados localmente na unidade C: em arquivos .txt.
- Opção para exportação em .csv.

## Observação Importante
Todos os dados usados neste projeto, incluindo nomes, CPFs, CNPJs, empresas e outras informações,
são **fictícios** e têm fins exclusivamente educacionais. 
**Nenhuma dessas informações reflete pessoas, empresas ou dados reais.**

## Referências
- Kernighan, B. W., & Ritchie, D. M. (1988). The C Programming Language.
- Pressman, R. S. (2014). Software Engineering: A Practitioner's Approach.
