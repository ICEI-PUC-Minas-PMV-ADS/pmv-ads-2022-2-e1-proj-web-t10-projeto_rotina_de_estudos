# Plano de Testes de Software

Os requisitos para realização dos testes de software são:

●	Site publicado na Internet

●	Navegador da Internet - Chrome, Firefox ou Edge

●	Conectividade de Internet para acesso às plataformas (APISs)

Os testes funcionais a serem realizados no aplicativo são descritos a seguir:                 

|Caso de Teste | CT-01- Visualizar se as páginas estão linkadas corretamente                                             |
|--|-------------------------------------------------------|
|Requisitos Associados| RF – 01 - O site deve apresentar na página inicial um texto de boas-vindas, contendo a ideia do projeto, para quem ele foi pensado e possibilitando o cadastro do usuário.RF-02 - Ao clicar em “Cadastre-se”, o usuário será direcionado para a página de cadastro, onde ele irá inserir seus dados pessoais e selecionar em qual perfil de estudante ele se encaixa: concurseiro ou vestibulando. RF-03 – Após efetuado o cadastro o usuário será direcionado para a página principal, de acordo com a sua seleção inicial (vestibulando ou concurseiro). O site deverá abrir a página principal que, se vestibulando, apresentará as áreas do conhecimento a serem preenchidas com os conteúdos e, se concurseiro, apresentará os conhecimentos específicos, legislação. Em ambos será possível acrescentar novos tópicos e adicionar novos conteúdos. |
|Objetivo do Teste | Verificar se as páginas estão associadas aos seus respectivos perfis: concurseiro e vestibulando.         |
|Passos| 1) Acessar o Navegador 2) Informar o endereço do Site 3) Visualizar a página principal 4) Visualizar a página de cadastro 5) Visualizar a sequência de páginas a partir do item selecionado: concurseiro ou vestibulando|
| Critérios de Êxito | ●	O site deverá ser acessado a partir de qualquer computador (PC) conectado à internet e com os requisitos mínimos descritos neste documento. ●	As páginas devem ser visualizadas corretamente no navegador, conforme prints apresentados no item 7. ●	Deve ser possível navegar de uma página para a outra mantendo a sequência de telas do item 7. ●	As páginas devem ser exibidas conforme o item selecionado pelo usuário: concurseiro ou vestibulando.|





|Caso de Teste | CT-02- Visualizar o progresso das tarefas                                             |
|--|-------------------------------------------------------|
|Requisitos Associados| RF-10 - O site deve permitir que o usuário acompanhe a evolução de seus estudos, aparecendo um indicador de tarefas cadastradas, não iniciadas, em andamento e concluídas. Conforme o usuário for atualizando o status de seus conteúdos, o número de tarefas é atualizado automaticamente e uma cor será atribuída: Vermelho - tarefas concluídas = 0 e Tarefas cadastradas > 0  Amarelo - tarefas concluídas > 0 e tarefas cadastradas > 0 Verde – tarefas concluídas == tarefas cadastradas. Após a verificação do progresso, o usuário poderá retornar para a página principal clicando em voltar. Se a quantidade de tarefas cadastradas, não iniciadas, em andamento e concluídas for igual a 0, uma dica será apresentada ao usuário lembrando-o de que é necessário iniciar os estudos.  |
|Objetivo do Teste | Verificar se o indicador colorido apresenta a cor vermelha quando todos os tópicos apresentarem o número 0. Verificar se a dica está aparecendo quando todas os tópicos apresentarem o número 0.        |
|Passos|1) Acessar o Navegador 2) Informar o endereço do Site 3) Visualizar a página Acompanhe aqui o seu progresso |
| Critérios de Êxito | A página deve apresentar o indicador vermelho e uma dica quando todos os tópicos apresentarem a quantidade 0 de tarefas cadastradas, não iniciadas, em andamento e concluídas. |





