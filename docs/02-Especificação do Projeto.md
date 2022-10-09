# Especificações do Projeto

<span style="color:red">Pré-requisitos: <a href="1-Documentação de Contexto.md"> Documentação de Contexto</a></span>

A definição do problema e pontos mais relevantes desse projeto foram pensados a partir de uma pesquisa bibliográfica que apontou o crescente interesse dos estudantes em participar de seleções de concursos. Os detalhes para a realização desse projeto foram consolidados a partir do perfil de pessoas que a ferramenta busca beneficiar.


## Personas

As personas levantadas no processo, estão listadas a seguir.

•	Tais Brandão tem 23 anos, é auxiliar administrativo e trabalha em uma empresa que produz equipamentos médicos. É concurseira e quer mudar de área pois não enxerga possibilidades de crescimento na sua carreira atual, ela enfrenta frustações no setor privado por ter pouco tempo para se dedicar a si mesma além do excesso de cobranças. Tais adora ler, fazer trilhas, viajar e praticar natação, é muito antenada com as mídias sociais e está em busca de uma ferramenta que a auxilie na gestão de tempo e organização das matérias de estudo.

•	Samuel Pereira tem 16 anos, é estudante do terceiro ano do ensino médio em escola pública e menor aprendiz. Almeja ingressar no ensino superior em uma universidade pública, mas sofre com a falta de organização com a rotina de estudos. Samuel é muito ativo nas redes sociais grava vídeos para o tiktok, instagram e youtube, gosta de ler, andar de skate e jogar vídeo game.

•	Gustavo Mendes tem 17 anos, está no terceiro ano do ensino médio em uma escola da rede privada, é vestibulando de medicina e estuda com dedicação total, tem dificuldade de organizar sua rotina de estudos, por ter muita matéria acumulada, sabe que medicina é um curso muito concorrido e por isso precisa de uma ferramenta que o auxilie na gestão do tempo, direcionando, mas tempo de estudo para as matérias que tem dificuldade. Apaixonado por música, Gustavo toca piano clássico, além de praticar hipismo, ler e se dedicar a aprendizagem de novas línguas como o francês.


•	Pamella Rodrigues tem 32 anos, casada, é concurseira, estuda com dedicação total aos concursos, mas tem encontrado dificuldades para conciliar a rotina de casa com os estudos. Por ter se formado a muitos anos, ela tem tido dificuldades em retomar as disciplinas básicas e precisa de uma ferramenta que possibilite a organização do tempo e do conteúdo. É uma pessoa tranquila que adora assistir Netflix e viajar com a família.

•	Antônio Carlos, tem 65 anos e é aposentado. Está buscando uma ferramenta que possibilite organizar uma rotina de estudos completa, mas que ao mesmo tempo seja simples de usar, por não ter muita familiaridade com aplicativos e redes sociais Antônio vem enfrentando um pouco de dificuldade de se organizar os conteúdos, depois de anos fora do mercado de trabalho decidiu assumir um novo desafio e retomar a rotina de trabalho para ter uma fonte de renda complementar a aposentadoria, além de suprir o tempo ocioso que passa em casa. Ele gosta de ler, jogar xadrez na praça aos domingos e passear com o seu cachorro.


## Histórias de Usuários

A partir da observação do dia a dia das personas identificadas para o projeto, foram registradas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Tais Brandão | Organizar os conteúdos de forma ordenada para a minha rotina | Assimilar todo o conteúdo necessário para aprovação em concurso |
|Samuel Pereira | Otimizar o tempo de estudo   | Para conquistar a aprovação em uma universidade pública  |
|Gustavo Mendes |Montar o cronograma de estudo focado nas matérias que tenho mais dificuldade |Para direcionar um tempo maior para essas matérias |
|Pamella Rodrigues | Cadastrar as disciplinas e estipular um prazo para cada matéria |Para conseguir estudar todo o conteúdo|
|Antônio Carlos |Orientação de como iniciar os estudos e usar a ferramenta em forma de tutorial |Para organizar o conteúdo  |


## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| O site deve apresentar na página inicial as boas-vindas e a opção para o usuário escolher se ele é um vestibulando ou concurseiro | ALTA | 
|RF-002| Ao selecionar qualquer uma das opções (vestibulando ou concurseiro), o usuário será direcionado para a página de cadastro, onde ele irá inserir seu nome completo, e-mail, CPF, telefone celular e concordar com os ternos e política de privacidade   | ALTA |
|RF-003 | Ao clicar em cadastrar, o usuário terá efetuado seu cadastro e seus dados e conteúdos ficarão salvos localmente no navegador. Ao finalizar o cadastro, o usuário será direcionado para a página principal, de acordo com a sua seleção inicial (vestibulando ou concurseiro). O site deverá abrir a página principal que, se vestibulando, apresentará as áreas do conhecimento a serem preenchidas com os conteúdos e, se concurseiro, apresentará os conhecimentos específicos, legislação. Em ambos será possível acrescentar novos tópicos e adicionar conteúdos | ALTA |
| RF-004 | Na página principal do vestibulando, o título apresentará o nome do usuário cadastrado e no canto superior, haverá os botões minha conta e relatório | ALTA |
| RF-005 | Na página principal do concurseiro, o título apresentará o nome do usuário cadastrado e no canto superior, haverá os botões minha conta, meu edital e relatório.  Haverá também uma dica incentivando o usuário a preencher as informações do edital no menu meu edital, para ter sempre as informações disponíveis | ALTA |
| RF-006 | Quando o usuário, vestibulando ou concurseiro, clicar em adicionar um novo conteúdo, abrirá a página para cadastro, onde ele deverá escolher um título para o conteúdo, fazer uma descrição do que ele irá estudar, podendo adicionar links de vídeos, artigos, links de outras páginas complementares, a fim de facilitar seu estudo. O usuário irá estipular um prazo para concluir o estudo deste tópico cadastrado e ir atualizando o status da tarefa em não iniciada, em andamento e concluída | ALTA |
| RF-007 | Quando o usuário finalizar o cadastro do novo conteúdo, ele será direcionado para a página principal e o novo conteúdo aparecerá embaixo do tópico em que foi adicionado. Conforme ele for adicionando novos conteúdos, os mesmos aparecerão na sequência em que forem adicionados, podendo ser editados ou excluídos| ALTA |
| RF-008 | Se o usuário desejar editar o conteúdo, ele irá clicar no botão editar na página principal e será direcionado para a página de edição, onde ele poderá alterar o título, a descrição, o prazo e o status. Caso esteja de acordo com as alterações ele irá salvar e suas informações serão atualizadas, depois o usuário será direcionado para a página principal e, caso não deseje realizar nenhuma alteração, ele irá clicar em cancelar e o conteúdo não será alterado, sendo o usuário direcionado para a página principal | MÉDIA | 
|RF-009 | Se o usuário desejar remover o conteúdo, ele irá clicar no botão remover na página principal e será direcionado para a página de remoção, onde ele poderá excluir o conteúdo selecionado ou cancelar a operação. Na página de remoção do conteúdo terá uma mensagem destacando que o usuário está prestes a remover o conteúdo que compõe sua rotina de estudos e que, uma vez removido, não será possível recuperá-lo. Caso esteja de acordo com a remoção do conteúdo, ele irá clicar no botão confirmar remoção e será direcionado para a página principal e, caso não deseje excluir, ele irá clicar em cancelar e o conteúdo não será alterado, sendo o usuário direcionado para a página principal | MÉDIA |
| RF-010 | Ainda na página principal terá o menu relatório, onde o usuário poderá acompanhar a evolução de seus estudos, aparecendo um indicador de tarefas cadastradas, não iniciadas, em andamento e concluídas. Conforme o usuário for atualizando o status de seus conteúdos, o número de tarefas é atualizado automaticamente e uma cor será atribuída:Vermelho - tarefas concluídas = 0 e Tarefas cadastradas > 0 Amarelo - tarefas concluídas > 0 e tarefas cadastradas > 0 Verde – tarefas concluídas == tarefas cadastradas. Após a verificação do progresso, o usuário poderá retornar para a página principal clicando em voltar. | MÉDIA |
 | RF-011 | Na página principal do concurseiro, no menu meu edital, o usuário poderá inserir o link do edital e fazer anotações úteis a serem consultadas ao longo dos estudos. Após inserir os itens, ele poderá deixar salvo, clicando em salvar, ou cancelar, caso não faça nenhuma observação, retornando para a página principal em qualquer uma das ações realizadas. | BAIXA |
 | RF- 012 | Na página principal terá o menu minha conta, onde o usuário poderá fazer alterações em seu cadastro ou excluir sua conta. Se o usuário desejar realizar alguma alteração, ele irá clicar em minha conta e será direcionado para a página de edição dos dados cadastrais. Na página de edição, o usuário poderá alterar seu nome, e-mail, CPF e telefone, clicando em salvar para atualizar as informações, sendo direcionado posteriormente para a página principal. Se o usuário não modificar nenhum dado e desejar voltar para a página principal, basta clicar em salvar que as informações serão mantidas. Caso o usuário deseje excluir sua conta, ele deverá clicar no botão vermelho excluir minha conta e uma mensagem aparecerá confirmando se ele realmente deseja remover sua conta e que, após a remoção, não será possível recuperá-la. Se o usuário estiver de acordo ele irá confirmar a exclusão e, caso contrário, irá cancelar a operação, clicando no botão cancelar | BAIXA |


### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| O site deve ser publicado em um ambiente acessível publicamente na Internet (GitHub Pages) | ALTA | 
|RNF-002| O site deverá ser responsivo permitindo a visualização em um celular de forma adequada |  ALTA | 
|RNF-003| O site deve ser compatível com os principais navegadores do mercado (Google Chrome, Firefox, Microsoft Edge)  | ALTA |
|RFN-004| O site deve ter bom nível de contraste entre os elementos da tela em conformidade  | MÉDIA |


## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue até o final do semestre |
|02| Não pode ser desenvolvido um módulo de backend        |
|03| A equipe não pode subcontratar o desenvolvimento do trabalho |


