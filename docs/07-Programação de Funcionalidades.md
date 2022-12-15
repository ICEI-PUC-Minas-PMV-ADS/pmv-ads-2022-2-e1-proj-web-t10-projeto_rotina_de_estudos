# 7-Funcionalidades do Sistema (Telas)

Nesta seção são apresentadas as telas desenvolvidas para cada uma das funcionalidades do sistema.

## Tela de Boas- Vindas (RF-01)
O site deve apresentar na página inicial um texto de boas-vindas, contendo a ideia do projeto e para quem ele foi pensado

![image](https://user-images.githubusercontent.com/115049890/207484533-20a28fcf-5f04-4ab5-9299-985a1d6d5368.png)

### Requisitos atendidos

●	RF-01 

### Artefatos da funcionalidade

●	index.html

●	style.css

●	Undraw.svg


Estrutura de Dados
  {
  
	"mensagens": [
		
    {
			"id": 1,
      
			"titulo": "Página Inicial do Projeto Rotina de Estudos",
      
			"data": "02/10/2022",
      
			"fonte": "Git Hub",
      
			"autor": "Grupo ADS PUC MG-Rotina de Estudos",
      
			"texto": "Olá estudante, seja bem-vindo ao Rotina de Estudos, o site que vai transformar a sua vida!..."
		} 
	]
} 


### Instruções de acesso

1. Abra um navegador de Internet e informe a seguinte URL https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2022-2-e1-proj-web-t10-projeto_rotina_de_estudos 
2. A tela de boas-vindas é a primeira funcionalidade exibida pelo aplicativo.

## Página de Cadastro (RF-02 e RF-03)

O usuário será direcionado para a página de cadastro, onde ele irá inserir seu nome completo, e-mail, CPF telefone celular e concordar com os ternos e política de privacidade. Ao clicar em continuar, o usuário terá efetuado seu cadastro e seus dados e conteúdos ficarão salvos localmente no navegador. Ao finalizar o cadastro, o usuário será direcionado para a página principal, de acordo com a sua seleção inicial (vestibulando ou concurseiro). O site deverá abrir a página principal que, se vestibulando, apresentará as áreas do conhecimento a serem preenchidas com os conteúdos e, se concurseiro, apresentará os conhecimentos específicos, legislação. Em ambos será possível acrescentar novos tópicos e adicionar conteúdo.

![image](https://user-images.githubusercontent.com/115049890/207485713-99785103-7142-489b-a55c-8cb0452c5db2.png)

### Artefatos da funcionalidade

●	style.css

●	Undraw.svg


### Instruções de acesso

3. Após clicar no botão de cadastre-se na página de boas-vindas, o usuário será redirecionado para a página de cadastro.
4. Nessa página o usuário informará seu nome, e-mail, celular gênero e senha.
5. Após preencher os campos devidos escolha a opção vestibulando ou concurseiro. 

## Página Principal Vestibulando (RF-04)

Na página principal do vestibulando, o título apresentará o nome do usuário cadastrado e no canto superior, haverá os botões minha conta e relatório.

![image](https://user-images.githubusercontent.com/115049890/207486124-77792fbb-51f5-41a8-9b90-53700bb68587.png)

### Requisitos atendidos

●	RF-04

### Artefatos da funcionalidade

●	index.html

●	style.css

### Instruções de acesso

6. Após clicar no botão de continuar na página de cadastro, o usuário será redirecionado para a página do vestibulando.
7. Nessa página o usuário pode adicionar os conteúdos pela área do conhecimento, voltar a conta e acessar os relatórios. 

## Página Principal Concurseiro (RF-05)

Na página principal do concurseiro, o título apresentará o nome do usuário cadastrado e no canto superior, haverá os botões minha conta, meu edital e relatório.  Haverá também uma dica incentivando o usuário a preencher as informações do edital no menu meu edital, para ter sempre as informações disponíveis.

![image](https://user-images.githubusercontent.com/115049890/207486358-2c138805-fcaa-4a98-b1f5-7668bbcbe5d5.png)

### Requisitos atendidos

●	RF-05

### Artefatos da funcionalidade 

●	index.html

●	style.css

### Instruções de acesso

8. Após clicar no botão de continuar na página de cadastro, o usuário será redirecionado para a página do concurseiro.
9. Nessa página o usuário pode adicionar os conteúdos do concurso, voltar a conta, acessar os relatórios e edital.

## Página Cadastro Conteúdo (RF-06 e RF-07)

Quando o usuário, vestibulando ou concurseiro, clicar em adicionar um novo conteúdo, abrirá a página para cadastro, onde ele deverá escolher um título para o conteúdo, fazer uma descrição do que ele irá estudar, podendo adicionar links de vídeos, artigos, links de outras páginas complementares, a fim de facilitar seu estudo. O usuário irá estipular um prazo para concluir o estudo deste tópico cadastrado e ir atualizando o status da tarefa em não iniciada, em andamento e concluída. Quando o usuário finalizar o cadastro do novo conteúdo, ele será direcionado para a página principal e o novo conteúdo aparecerá embaixo do tópico em que foi adicionado. Conforme ele for adicionando novos conteúdos, eles aparecerão na sequência em que forem adicionados, podendo ser editados ou excluídos.

![image](https://user-images.githubusercontent.com/115049890/207486745-0244ec3a-3e3a-4585-8b29-203f36d47423.png)

### Requisitos atendidos

●	RF-06 e RF-07

### Artefatos da funcionalidade

●	index.html

●	style.css

### Instruções de acesso

 10. Após clicar no botão de adicionar conteúdo na página principal do concurseiro ou vestibulando, o usuário será redirecionado para a página de adição de conteúdo.
 11. Nessa página o usuário pode adicionar os conteúdos do concurso ou vestibular, estabelecendo um título para a tarefa seguido da descrição. Também será possível estabelecer um prazo para terminar a tarefa e escolher o seu status.


## Página Edição Conteúdo (RF-08)

Se o usuário desejar editar o conteúdo, ele irá clicar no botão editar na página principal e será direcionado para a página de edição, onde ele poderá alterar o título, a descrição, o prazo e o status. Caso esteja de acordo com as alterações ele irá salvar e suas informações serão atualizadas, depois o usuário será direcionado para a página principal e, caso não deseje realizar nenhuma alteração, ele irá clicar em cancelar e o conteúdo não será alterado, sendo o usuário direcionado para a página principal.

![image](https://user-images.githubusercontent.com/115049890/207486959-0140785a-5271-4f86-9081-5ab79f2205b1.png)

### Requisitos atendidos

●	RF-08

### Artefatos da funcionalidade

●	index.html

●	style.css

### Instruções de acesso

12. Nessa página o usuário pode editar as informações do conteúdo cadastrado, como o título, descrição, prazo e status.

## Página Remoção de Conteúdo (RF-09)

Se o usuário desejar remover o conteúdo, ele irá clicar no botão remover na página principal e será direcionado para a página de remoção, onde ele poderá excluir o conteúdo selecionado ou cancelar a operação. Na página de remoção do conteúdo terá uma mensagem destacando que o usuário está prestes a remover o conteúdo que compõe sua rotina de estudos e que, uma vez removido, não será possível recuperá-lo. Caso esteja de acordo com a remoção do conteúdo, ele irá clicar no botão confirmar remoção e será direcionado para a página principal e, caso não deseje excluir, ele irá clicar em cancelar e o conteúdo não será alterado, sendo o usuário direcionado para a página principal. 

![image](https://user-images.githubusercontent.com/115049890/207487166-3a8e1e06-419c-4f2d-9181-1b1270a92c98.png)

### Requisitos atendidos

●	RF-09

### Artefatos da funcionalidade

●	index.html

●	style.css

●	Undraw.svg

### Instruções de acesso

13. Nessa tela o usuário remove a tarefa cadastrada clicando em Remover.

## Página Acompanhe aqui o seu progresso (RF-10)

Na página principal, o usuário poderá acessar o tópico relatório, que direcionará o usuário à página que permite acompanhar o seu progresso. Nesta página o usuário acompanhará a quantidade de conteúdos cadastrados, as tarefas não iniciadas, em andamento e as concluídas. Se o usuário estiver com várias atividades cadastradas e nenhuma concluída, aparecerá uma dica para que ele inicie os estudos. Se a quantidade de tarefas cadastradas e concluídas forem iguais, o usuário receberá uma mensagem de parabéns como incentivo. Ele poderá acompanhar o status de sua evolução pelo indicador colorido posicionado em frente o tópico meu desempenho. Se não houver iniciado nenhuma atividade o círculo ficará vermelho, quando estiver com tarefas em andamento ficará amarelo e quando concluir todos os conteúdos, ficará verde. Após a conferência, o usuário retornará à página principal clicando em voltar.

![image](https://user-images.githubusercontent.com/115049890/207487385-de460cb4-14bc-46ab-934a-cd53000ee006.png)

### Requisitos atendidos

●	RF-010

### Artefatos da funcionalidade

●	index.html

●	style.css

●	Undraw.svg

### Instruções de acesso

14. Nessa tela o usuário acompanha o seu progresso através de indicadores nas cores vermelho – tarefas não iniciadas, amarelo – tarefas em andamento, verde – tarefas concluídas. 


## Página Adicionar Edital (RF-11)

Na página principal do concurseiro, no menu meu edital, o usuário poderá inserir o link do edital e fazer anotações úteis a serem consultadas ao longo dos estudos. Após inserir os itens, ele poderá deixar salvo, clicando em salvar, ou cancelar, caso não faça nenhuma observação, retornando para a página principal em qualquer uma das ações realizada

![image](https://user-images.githubusercontent.com/115049890/207754522-94bb46b4-153d-4fca-8d8e-b9f3fe7281c6.png)


### Requisitos atendidos

●	RF-011

### Artefatos da funcionalidade

●	index.html

●	style.css

●	Undraw.svg

### Instruções de acesso

15. Nessa tela o usuário adiciona o edital clicando em salvar.


## Página Edição de Cadastro e Exclusão de conta (RF-12)

Na página principal terá o menu minha conta, onde o usuário poderá fazer alterações em seu cadastro ou excluir sua conta. Se o usuário desejar realizar alguma alteração, ele irá clicar em minha conta e será direcionado para a página de edição dos dados cadastrais. Na página de edição, o usuário poderá alterar seu nome, e-mail, CPF e telefone, clicando em continuar para atualizar as informações, sendo direcionado posteriormente para a página principal. Se o usuário não modificar nenhum dado e desejar voltar para a página principal, basta clicar em salvar que as informações serão mantidas. Caso o usuário deseje excluir sua conta, ele deverá clicar no botão vermelho excluir minha conta e uma mensagem aparecerá confirmando se ele realmente deseja remover sua conta e que, após a remoção, não será possível recuperá-la. Se o usuário estiver de acordo ele irá confirmar a exclusão e, caso contrário, irá cancelar a operação, clicando no botão cancelar.

![image](https://user-images.githubusercontent.com/115049890/207487796-9a91a01e-8630-4be8-b35e-47991015f52c.png)

![image](https://user-images.githubusercontent.com/115049890/207754579-2aad1b26-75ff-459a-b384-e2ed8951dac1.png)


### Requisitos atendidos

●	RF-012

### Artefatos da funcionalidade

●	index.html

●	style.css

●	Undraw.svg

### Instruções de acesso

16. Na tela de edição o usuário edita as informações de cadastro clicando em confirmar.
17. Na tela de remoção da conta o usuário encerra a conta clicando em confirmar exclusão.


