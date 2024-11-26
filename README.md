# Projeto Final


- [Sobre](#sobre) Esse projeto é uma avaliação final do curso de Residência em TIC, da trilha fullstack. Esse projeto é um portfólio mostrando as principais coisas sobre mim.

- [Autor](#autor) Mateus Menezes Helcias
- [Funcionalidades](#funcionalidades) Dar uma visão de quem eu sou.

- [Tecnologias](#tecnologias) AS tecnologias utilizadas foram HTML e CSS


## Sobre mim
Sou Mateus Menezes Helcias, tenho 23 anos e sou natural de Morrinhos, Ceará. Sou uma pessoa determinada, paciente e organizada, focada em aprimorar habilidades e alcançar metas. Atuo na área de tecnologia, cursando Ciência da Computação. Sou fascinado por aprendizado contínuo e constantemente busco me desenvolver, seja em novas tecnologias, em oratória ou no inglês, que estou estudando atualmente


## Principais comandos GIT
- GIT INIT →  É usado para criar um repositório GIT local vazio, permitindo começar o rastreamento das modificações. Ao inicializar o git init, o git  não vai rastrear automaticamente, é preciso adicionar os arquivos no diretório antes de fazer um commit.
- GIT ADD <nome> → Adiciona o arquivo para o estágio de stage. Aqui está pronto para ser commitado.
- GIT ADD . → Adiciona todos os arquivos para o estágio de stage.
- GIT RM —cached <nome> → Ele tira o arquivo do estágio de stage e retorna para o modificado.
- GIT COMMIT -M → Faz um commit com uma mensagem identificando o que está modificando.
- GIT LOG → Mostra todos os commits com seus dados.
- GIT LOG —oneline → Mostra os commits com dados mais simplificadas.
- GIT CHECKOUT <id do commit> → Retorna para o commit indicado, mas não faz nenhuma alteração, somente visualização.
- GIT CHECKOUT MAIN → retorna para o commit atual.
- GIT REVERT <id do commit> → Desfaz um commit.
- GIT RESET <id do commit> → Desfaz todo os commits a partir do commit selecionado(Todas as modificações retornarão para o estágio de modified)
- GIT RESET <id do commit> —hard → Desfaz e apaga tudo até o commit selecionado.
- GIT CONFIG —GLOBAL  —LIST → Vai listar as configurações globais do git.
- GIT CONFIG —GLOBAL [user.name](http://user.name) = <nome> → Vai setar um nome de usuário globalmente.
- GIT CONFIG —GLOBAL [user.email](http://user.email) = <email> → Vai setar um email de usuário globalmente.
- GIT RESTORE —staged <arquivo> → remove o arquivo do estagio de stage
- GIT BRANCH → mostra todas as branches do projeto.
- GIT BRANCH <nome> → Adiciona uma nova branch ao projeto.
- GIT CHECKOUT -b <nome> →  Cria uma branch, mas com o -b ja vai mudar para o branch criado.
- GIT BRANCH -d <nome> → Deleta uma branch.
- GIT BRANCH -m <nome> → Altera o nome da branch.
- GIT MERGE <nome da branch>→  Adiciona a branch dentro de outra.
- GIT diff <branch a ser merged> → Mostra onde estão as diferenças.
- GIT diff <branch a ser merged> —check → retorna os arquivos de conflitos.
- GIT PULL <SSH> <nome da branch> → para baixar projeto do github.
- GIT PUSH <SSH><nome da branch>→  Leva o que tem na maquina desse branch para dentro do repositorio no github.
- GIT REMOTE add origin <SSH ou link do repositorio>→ padroniza o caminho para o nome ”origin” para que não seja necessário indicar sempre o caminho.
- GIT REMOTE REMOVE ORIGIN→ remove o padrão origin
- GIT PUSH ORIGIN <branch> → Adiciona a branch/atualização dentro do repositório github.
- GIT PUSH  -U ORIGIN MAIN → Manda os arquivos para o github e associa a branch local com a branch remota..
- GIT CLONE <SSH> → Faz um clone do projeto do github.
- GIT PULL ORIGIN MAIN → Vai trazer as atualizações do github.