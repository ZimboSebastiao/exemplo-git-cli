# Exemplos de operações básicas para git via CLI

## Comandos de uso geral da CLI

- Criar pasta: mkdir nomepasta
- Listar conteúdo: dir
- Limpar tela: cls
- Entar na pasta: cd nomepasta 

## Comandos principais do git



`git config  user.name` e `git config  user.email`

Verificar usuário/email

`git config  --global user.name "Seu nome com quiser"`  e  
`git config --global  user.email "seuemail@provedor.com"`

Mudar usuário e e-mail de forma global

**obs:** normalmente estes dados estão relacionados ao usuário/conta do site Github


`git init`

Inicializar um repositório (executado dentro da pasta).

`git branch nome-branch-atual nome-branch-nova`

Renomear branches

Para alterar a branch de **master** para **main** (novo padrão), usaríamos: `git branch master main`

`git status`

Verificar o status atual.

`git add nomearquivo`

Adicionar (Tornar rastreável) ao monitoramento do git.

`git commit -m "texto da mensagen sobre a alteração"`

fazer commit das alterações (salvar no historico).

`git remote add origin endereço-do-repositório.git`

adicionar/conectar o repositório remoto ao local.
