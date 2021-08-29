STATUS -> Visualiza os status de quais arquivos foram modificados

ADD -> Adiciona os arquivos modificados para staging(preparação)

COMMIT -> Cria um novo commit(registro de modificações) na ramificação

PUSH -> "EMPURRA" os commits locais para a ramificação remota



### Conceitos de Ramificações

O Git pode atender várias pessoas que trabalham em um mesmo projeto. 

Para isso o projeto pode ter mais de uma ramificação de trabalho.

A ramificação nada mais é do que uma nova linha de desenvolvimento que não afeta a linha principal (main). 

Para que todos possam alterar os arquivos sem tornar a ramificação principal uma bagunça, é importante que cada pessoa crie sua branch e trabalhe apenas nela. 

Caso alguém trabalhe em mais de uma frente de projeto, é possível que mantenha mais de uma branch.



### Conceitos HEAD e WORKSPACE

WORKSPACE é o seu espaço de trabalho atual

HEAD é o ponto de partida do seu desenvolvimento, é o PARENT do seu próximo COMMIT.

Todo o Git é baseado em COMMITS que são filhos de outros COMMITS. 

O HEAD pode estar apontado para uma BRANCH (ramificação) ou para um COMMIT em específico.


### Git diff

"Diff" de diferença, basicamente ele mostra o conteúdo modificado entre nos arquivos do **WORKSPACE** e do **HEAD**.

Também serve para verificar diferenças entre duas branchs, dois commits, dois arquivos... etc