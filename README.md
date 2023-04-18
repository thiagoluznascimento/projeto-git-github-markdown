# Olá, este codigo está me servido de estudo para melhorar minhas praticas com o Git / GitHub e sintax Markdown.

## Introdução

GitHub é uma plataforma de hospedagem de código para controle de versão e colaboração. Permite que você e outras pessoas trabalhem em conjunto em projetos de qualquer lugar.

Este tutorial ensina os princípios básicos de GitHub como, por exemplo, repositórios, branches, commits e pull requests. Você criará seu próprio repositório Hello World e aprenderá o fluxo de trabalho de pull request de GitHub, uma maneira popular de criar e revisar o código.

Neste guia de início rápido vamos aprender:

- Criar e usar um repositório
- Iniciar e gerenciar um novo branch
- Fazer alterações em um arquivo e enviá-los por push para GitHub como commits
- Abrir e realizar merge de um pull request

Um repositório geralmente é usado para organizar um único projeto. Os repositórios podem conter pastas e arquivos, imagens, vídeos, planilhas e conjuntos de dados - tudo o que seu projeto precisar. Geralmente, os repositórios incluem um arquivo README, um arquivo com informações sobre seu projeto. Os arquivos README são escritos na linguagem Markdown em texto sem formatação. Use esta [folha de referências](https://www.markdownguide.org/basic-syntax) para começar a usar a sintaxe Markdown. O GitHub permite adicionar um arquivo README ao mesmo tempo em que você cria seu repositório. GitHub também oferece outras opções comuns, como um arquivo de licença.


### Para criar um novo repositério:
1. No canto superior direito de qualquer página, use o menu suspenso **+** e selecione **Novo repositório**.

![Imagem](https://docs.github.com/assets/cb-11427/mw-1000/images/help/repository/repo-create.webp)

2.Na caixa "Nome do repositório", *digite nome-do-repositorio*

3. Na caixa "Descrição", digite uma breve descrição.

4. Selecione se o repositório será **Público** ou **Privado**.

5. Caso queira selecione **Adicionar** um arquivo **README**

6. Clique em **Criar repositório**.


## Criar um branch 

O Branch permite que você tenha diferentes versões de um repositório de uma só vez.

Por padrão, seu repositório tem um branch chamado main que é considerado o branch definitivo. Você pode criar branches adicionais com base em main no repositório. Você pode usar branches para ter diferentes versões de um projeto de uma só vez. Isso é útil quando você deseja adicionar novas funcionalidades a um projeto sem alterar a principal fonte de código. O trabalho feito em diferentes branches não aparecerá no branch principal até que você faça o merge, que abordaremos mais tarde neste guia. Você pode usar branches para fazer experimentos e edições antes de fazer commit delas em main.

Quando você cria um branch com base no branch main, você faz uma cópia ou um instantâneo de main como ele era naquele momento. Se outra pessoa fez alterações no branch main enquanto você estava trabalhando no seu branch, você pode efetuar pull dessas atualizações.

Este diagrama mostra:

- O branch main
- Um novo branch chamado feature
- O percurso que o feature faz antes de ser mesclado em main

![Imagem](https://docs.github.com/assets/cb-23923/mw-1000/images/help/repository/branching.webp)

