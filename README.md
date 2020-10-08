# GoPass
> Sistema de reservas e compras de passagens aéreas.

### Funcionalidades principais

O sistema deverá realizar a reserva e pagamento de passagens aéreas, podendo o usuario realizar filtros incluindo origem/destino, datas, por relevancia, por melhor preco,

  - Logar no sistema GoPass, se for a primeira vez efetuar o cadastro
  - Efetura uma reserva de passagem disponível
  - Efetuar o pagamento de uma reserva (Meio de pagamentos)  

### Características

  - Consultar passagens aéreas disponíveis para efetuar possíveis reservas
  - Realizar consultas das passagens reservadas ou pagas.
  
Você também pode:
  - Cancelar a qualquer momento uma reserva
  - Visualizar o histórico das passagens do usuário

### Tecnologia

Segue arquitetura, linguagem e componentes utilizados na aplicação:

* [Visual Studio] - IDE utilizada para desenvolvimento da aplicação!
* [IdHTTP] - Componente utilizado para efetuar o GET do arquivo a ser baixado
* [idAntiFreeze] - Não permite o congelamento da tela
* [SaveDialog] - Permite a escolha do caminho a ser salvo o arquivo
* [idSSLIOHandlerSocketOpenSSL] - Utilizado na escolha da(s) versão(ões) do SSL
* [FDConnectio] - Utilizado para conectar com o banco de dados "SQLite"
* [FDQuery] - Utilizado para realização das consultas e inserções na tabela de log

## Papeis
  - __Product Owner:__ Helton Lizandro
  > Devido a uma maior familiaridade com a regra de negocio, foi nomeado como Product Owner.
  - __Scrum Master:__ Stewart Santos
  > Por ter uma certa vivencia com as cerimonias.
  - __Dev Team:__ Elizeu, Helton, Stewart

### Cerimoniais do Scrum

#### Backlog Produto
  - login/logout
  - Função de validação de usuário e senha
  - Cadastro de Usuário
  - Vdlidação de duplicidade de CPF no cadastro do usuário
  - Perfil do Usuário
  - Dados de perfil
  - Histórico de reservas
  - Busca de passagens disponíveis
  - Checkout (Confirmação do pagamento)
  - Passagens compradas/reservadas (Favoritar passagens)
  - Passagens favoritas 
  - Integração com redes sociais (Compartilhar Passagem)

#### Sprint Planning
  > Planejamentos de como seriam os Epicos candidatos a primeira sprint e atribuicao de pontuacao para ordenacao no backlog do produto. 
  
#### Sprint Backlog
  - [ ] Repositório GIT;
  - [ ] README do GIT;
  - [ ] Critérios da escolha da Equipe;
  - [ ] Pontos positivos e a melhorar da equipe;
  
#### Daly Meeting
> Reunioes do time para discussoes de features e regras de negocios, andamento de tasks e atribuicoes das mesmas. duracao normal de 15 min. 

#### Sprint Review
> ainda ira acontecer dia 09

#### Sprint Retrospective
> ainda ira acontecer dia 09  

#### Critérios de Escolha do time
  - Trabalho em equipe
  - Facilidade de se comunicar  
  

|integrante|pontos positivos|observacao de melhoria|
|-|-|-|
|Elizeu |Facilidade e comunicação e interação entre a equipe|Domínio e conhecimento de: C#/.Net, Azure DevOps.|
|Helton |Analítico e detalhista|Domínio e conhecimento de: C#/.Net, Azure DevOps.|
|Stewart|Facilidade de Gestão de Projeto, analise de requisitos|Domínio e conhecimento de: C#/.Net, Azure DevOps.|
