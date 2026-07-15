# 🚀 Desafio: Praticando Git, GitHub e Markdown

Este repositório foi criado como um projeto prático para consolidar o aprendizado sobre o ecossistema Git e GitHub. O objetivo principal é simular um ambiente real de desenvolvimento colaborativo, explorando desde a formatação de documentos com **Markdown** até o gerenciamento de tarefas usando **Issues**, **Branches** e **Pull Requests**.
---
## 🎯 Objetivos do Projeto


1. **Configurar o repositório público e o arquivo README.md** [X]
   - i. Utilizar o editor web GitHub.dev para realizar edições rápidas no navegador. [X]
   - ii. Garantir que o repositório esteja configurado como público para visualização da comunidade. [X]
2. **Praticar a sintaxe de formatação com Markdown**
   - i. Organizar o texto de forma estruturada usando títulos, subtítulos e listas. [X]
3. **Dominar os comandos essenciais do Git** [ ]
   - i. Realizar alterações locais e preparar os arquivos usando o comando `git add`. [ ]
   - ii. Salvar o progresso com mensagens de commit claras e enviar as alterações com `git push`. [ ]
4. **Simular colaboração em equipe no repositório**
   - i. Convidar um colaborador (ou conta secundária) para participar do projeto. [X]
   - ii. Realizar o clone do projeto localmente para simular o fluxo de trabalho de múltiplos desenvolvedores. [X]
5. **Dominar o fluxo de trabalho com Issues e Pull Requests**
   - i. Criar e documentar issues para organizar as tarefas pendentes do projeto. [X]
6. **Adicionar os principais comandos GIT** [ ]
   - i . Criar uma lista dos principais comandos que são utilizados no dia-a-dia. [ ]
---
## 💻 Guia Rápido de Comandos Git

Aqui está uma "colinha" dos comandos Git mais utilizados no dia a dia para referência rápida.

### 1. Inicialização e Clonagem
*   `git init`: Inicializa um repositório Git local na pasta atual.
*   `git clone <url-do-repositorio>`: Baixa uma cópia de um repositório remoto para a sua máquina.

### 2. Ciclo de Trabalho (Salvar Alterações)
*   `git status`: Exibe o estado atual dos arquivos (quais foram modificados, deletados ou criados).
*   `git add <nome-do-arquivo>`: Prepara um arquivo específico para o próximo commit.
*   `git add .`: Prepara **todos** os arquivos modificados de uma só vez.
*   `git commit -m "Sua mensagem aqui"`: Grava as alterações salvas na história do repositório local com uma mensagem descritiva.

### 3. Sincronização com o GitHub
*   `git push origin <nome-da-branch>`: Envia seus commits locais para o repositório remoto no GitHub.
*   `git pull`: Baixa e mescla (merge) as atualizações do GitHub no seu repositório local.
*   `git fetch`: Baixa o histórico do servidor remoto, mas sem alterar seus arquivos locais diretamente.

### 4. Ramificações (Branches) e Organização
*   `git branch`: Lista todas as branches locais do projeto.
*   `git branch <nome-da-branch>`: Cria uma nova ramificação.
*   `git switch <nome-da-branch>`: Altera o foco para a branch especificada.
*   `git checkout -b <nome-da-branch>`: Atalho para criar uma nova branch e já mudar para ela ao mesmo tempo.
*   `git merge <nome-da-branch>`: Junta as alterações da branch especificada com a sua branch atual.

### 5. Histórico e Desfazer Alterações
*   `git log --oneline`: Exibe o histórico de commits de forma resumida e organizada.
*   `git restore <nome-do-arquivo>`: Descarta as alterações locais de um arquivo que ainda não foram salvas.
