Formação fullstack

Links importantes: 
https://github.com/iamismile/web-dev-resources
https://www.csszengarden.com/
https://www.freecodecamp.org/portuguese/learn/
https://css-tricks.com/snippets/

Link do projeto no figma: https://www.figma.com/design/cfb4F7ZXMFQmvmTn3PKI4z/DRIP-STORE---DIGITAL-COLLEGE?node-id=101-2&t=k6NC3XeWSmAG6qwY-0

Aula dia 13/06

 Manifesto ágil
 - Scrum é uma ferramenta usada para aplicar as ideias do manifesto
 - Scrum é fundamental para líderes e gerente de equipe, porém é interessante o dev entender 

 Scrum 
 - Sprints (divisão de ciclos de produção)

 - Cerimônia 
  -> Plannig (planeja a execução das sprints),
  -> Dayli (reunião diária de oq fez ontem, oq tem pra hoje e se tem algum bloqueio)
  -> Retrospectiva (é discutido as coisas que deram e não deram certo e oq pode ser feito para melhorar o desenvolvimento da sprint)

 - Artefatos
  -> Usa-se ferramentas para acompanhar e registrar as tarefas (product backlog)

Kanban (usado com e sem scrum)
 - Usado para colocar as tarefas da sprint
 - Separado em 3 etapas: To Do - Doing e Done

Poker planning
 - Usado para criar pontuação nas atividades e assim entender o peso de cada coisa
 - Gera previsibilidade de entrega
 - Possibilita a criação de métricas

 3 papéis fundamentais no scrum:
 - Scrum master,
 - Product Owner,
 - Equipe de desenvolvimento

*Aula 14/06*

- Comandos no terminal:
pwd - ver local que estamos
ls - listar o que tem dentro da pasta
clear ou control + L - limpar
cd + nome da pasta - entrar em pasta
cd + enter - vai pra home 
cd + / - vai para raiz
ls -a - exibe os arquivos anônimos
touch - criar pasta

*Aula 17/06*

- Elemento Form
Tipos de input

*Aula 18/06*

- Padding
- Margin
- Espaçamento de texto -> letter-spacing e line-height
- Display: block, inline, inline-block, none, flex, grid
 -> none: remove o elemento da tela
 -> block: se aplica a elementos de bloco, ex: tag p, h, div e etc
 -> inline: se aplica em elementos que não precisam estar em bloco, ex: tags a, img, spam
 -> inline-block: posiciona dois elementos de bloco em uma linha, porém com o display flex essa função não é mais tão utilizada. Tag buttom é inline-block
 -> flex: usado sempre no elemento pai, quando ativado o display flex, libera inumeras possibiidades para essa função

- Media Query
É a capacidade de escrever o estilo de acordo com o tamanho da tela, gerando responsividade.
E decladado por @media

- Abordagem de layout
Aplicação de grid para organização da interface

- Links da aula:
https://www.maujor.com/tutorial/layout-css-passo-a-passo.php
https://www.homehost.com.br/blog/criar-sites/tabela-html/
https://maujor.com/tutorial/usando-jaws-para-testes.php#intro
https://developer.mozilla.org/en-US/docs/Web/CSS/box-align
https://flexboxfroggy.com/
https://www.w3schools.com/css/css_pseudo_elements.asp
https://www.w3schools.com/css/css_rwd_mediaqueries.asp
https://shellshock.io/#6ABT23D
https://www.conventionalcommits.org/en/v1.0.0/

- Pseudoclasse e pseudoelemento

- Github
Comandos git:
 -> Para configurar a máquina que você está com o git:
   git config
   git init
   git config user.name "WanessaT"
   git config user.email "wanessatlsousa@gmail.com"

   git status - identifica qual status do seu arquivo, onde ele está

   git pull origin main - trazer a pasta que está remota para a minha máquina


*Aula 19/06*

- Comandos git
- Link avaliação HTML e CSS:
https://github.com/digitalcollegebr/fullstack-avaliacoes/tree/main/Modulo_I/II-HTML_e_CSS/imagens

- Listar branchs do projeto:
git branch -a

- Criar uma branch separada da main:
git branch -a "Nome da branch"

- Voltar para a main:
git checkout main

*Aula 20/06*

- Criar branch e já navegar para ela:
git checkout -b nova-branch

- Para navegar entre commits:
git checkout +id do commit (pode usar os 8 primeiros digitos do commit)

- Para ver o id dos commits:
git log (mais detalhado)
git log --oneline (exibe de forma resumida)

- Para realizar o merge:
git merge nome-da-branch (normalmente o merge vai para a master)

*Aula 24/05*

- Npm -> Gerenciador de pacotes para usar nos nossos projetos no node e js. Criou-se o yarn para ser concorrente do npm
- Bootstrap não tem dependencia de outros pacotes
- Bundlephobia
- Sempre que estiver em um projeto usando o nopm, tem que criar um git ignore para a pasta node modules
