# Aprendizado por Projeto Integrado (API)

Repositório para armazenamento de projetos de API, ensinando na plataforma digital "GitHub". 

Projeto baseado na metodologia ágil SCRUM, procurando desenvolver a Proatividade, Autonomia, Colaboração e Entrega de Resultados dos estudantes envolvidos no projeto

# Índice
* [Objetivo do Projeto](#objetivo-do-projeto)
* [Funcionalidades e registros (vídeos e apresentações) das sprints](#funcionalidades-e-registros-(vídeos-e-apresentações)-das-sprints)
* [Backlog do produto](#Backlog-do-produto)
* [Competências desenvolvidas](#competências-desenvolvidas)
* [Autores](#autores)
  

# Projeto (API) 
Projeto pedagógico alicerçado na Metodologia API para ensino-aprendizado focado no desenvolvimento de competências e fundamentada nos pilares de aprendizado com problemas reais (RPBL), validação externa e mentalidade ágil. 
Uso de estratégias para entender o problema, conceber uma solução viável ao desenvolver e implementar o MVP seguido de sua operação (CDIO). 
Os resultados dos projetos devem obedecer ao Aviso Legal disponível no site da Fatec SJC com definição das datas do kickoff e das sprints

Sprint | Previsão | Status|
|------|--------|------|
|Kick Off | 28/08/2024 | Concluído|
|01 | 09/09/2024 | Em progresso|
|02|  30/09/2024| a fazer |
|03| 21/10/2024 | a fazer|
|Feira de Soluções|12/12/2024 |a fazer |





# Objetivo do Projeto

  O projeto na qual está sendo estudado e desenvolvido tem como objetivo usar, aprender e solucionar a situação na qual o cliente se encontra para que possamos propor o problema enfrentado por ele. A logistica especialmente no setor de bebidas, é uns dos pilar do sucesso da organização, pois ele e volve varios processos individuais que se não tiver a devida atenção e admimistração correta pode gerar além de perdas financeira, perda de dados e prejudica a relação com o cliente. A empresa visa melhorar sua gestão na logistica, obtendo uma visão mais clara da operação, desde da organização do frete até mesmo otimização da frota dos caminhões, visando reduzir os erros e maximizar a eficiencia da operação.
Nessa Sprint nosso foco será mostrar os problemas de forma mais clara, com o foco na ferramenta do Excel, onde possamos mostrar os dados de forma organizada.

* *Analisar e organizar os dados fornecidos pelo cliente:*
  
  A analise foi feita encima dos passados a nós do cliente, os dados foram organizado no excel na qual fizemos comparativos para explicar o problema da empresa e deixar de forma clara essses erros que vão desde de erro de frete como CIF E FOB, até nas datas de emissão dos pedidos até a entrega desses produtos.

* Organização dos fretes:
  
  A organização dos fretes é um ponto muito importante no estabelecimento pois possui prazo, custo, quantidade de carregamento, local a ser levado, entre outros.
Nosso objetivo foi mostrar onde que está a situação de quantos estão errados entre o propio CIF e o FOB, para ver em Fabrica está tendo erro de gestão e quanto está perdendo de dinheiro.

* Emissão de pedidos e entrega:
  
  Tem como proposta mostrar a incopatiblidade dos dados, onde em algumas situações a emissão do pedido é feita dias depois da entrega, como é possivel o pedido ser entegue antes da propia emisão do pedido? Este era o questionamento.
  
* Conferencia da capacidade dos caminhões e das rotas das entregas:
  
  A comferencia dos caminhões é imoorte para ver se não esta indo  corretamente nas entregas, no caso do cliente é os caminhões P24 e P12, temos como objetivo identificar se está indo corretamente com a carga solicitada para que não ocorra entregas erradas, pois isso pode constar no dados erro de transporte

# Funcionalidades e registros das sprints

  Para o projeto foi usado ferramentas como Excel, Power BI e o MySQL, para utilização nós dados coletados, na qual será desenvolvido um dashboard que apresente visualmente todos os dados importes para a análise de maneira fácil, objetiva e visual ao projeto.
  As empresas têm muita dificuldade na distribuição e nos transportes dessas operações tendo desde erros desde na hora do carregamento até a entrega ao cliente, lembra que a pontualidade e eficácia nas entregas trás confiança ao consumidor assim criando laços e num ramo de cervejaria onde o fluxo é bem constante e variado, cada erro logístico pode custar caro e isso mostra uma falha no processo da empresa.
  A empresa trabalhada no projeto quer ter uma visão ampla do setor logistico dela, para que possa melhorar a eficiência, tendo assim um setor bem estruturado, para tanto economicamente e estruturalmente.

## Tecnologias Utilizadas

# Excel

* O Excel foi a ferramenta mais utilizado por nós nessa API, foi fundamental na organização e na ánalise dos dados, possibilidado fazer comparações, planilhas e deixando em evidencia o problema que a empresa enfrenta, permitindo assim nos aprofundar de forma objetiva nos objetivos que queriamos chegar.

![image](https://github.com/user-attachments/assets/656c9d18-e331-4b7b-b826-8c60700f9c7d)

* Item acima é a dashboard de todos dados levantado, para que pudessemos tirar conclusão dos dados.
![image](https://github.com/user-attachments/assets/eb0d77c2-a162-465c-bf32-0de755a0ede5)
* A formula usada para fazer a verificação dos paletes: =SE(E(H2="P24";I2=24);"VERDADEIRO";SE(E(H2="P12";I2=12);"VERDADEIRO";"ERRO"))
  ![image](https://github.com/user-attachments/assets/1a934f26-88d0-48c4-9559-b177983c5954)

  
* Formula usada para fazer a veriificação do frete: =SE(E(G2="FOB";L2=0);"VERDADEIRO";SE(E(G2="CIF";L2<>0);"VERDADEIRO";"ERRO"))
  ![image](https://github.com/user-attachments/assets/6afc5418-0f29-49c0-ba57-97da1e70080f)

* Formula usada para fazer a veriificação das datas de entrega: =B2-A2

  ![image](https://github.com/user-attachments/assets/50edbc26-b1d7-4bd4-8d86-dfb6740d7117)

# Power BI
* Foi usado para organizar de forma visual, nosso objetivo é montar uma Dashboard que ireimos aprofundar mais a fundo no proximo semestre.
  ![image](https://github.com/user-attachments/assets/d10a5bcc-e577-4164-a00a-dba08b65a3a4)

# MySql
* Utilizado para integrar dados disponibilizados para acriação de um banco de dados relacional, capaz de ser utilizado para a criação de um dashboard no software Power Bi.
![{7BDDB080-9F5E-4977-9AF3-C18EBE713F1B}](https://github.com/user-attachments/assets/bafd1e8b-ee3b-4e8f-a202-4aa1b6722222)
Utilizando o create view é possível consultar dados especificos rapidamente sem a necessidade de digitar um código de comando novamente.


# Word
* Foi utilizado para fazer a documentação do trabalhado e forma simples fazer algumas anotações da API.
* [RELATORIO SPRINT 1- SPARTANS.pdf](https://github.com/user-attachments/files/17236296/RELATORIO.SPRINT.1-.SPARTANS.pdf)

#	GITHUB
* Permitiu que pudessemos apresentar o desenvolvimento do trabalho de forma visual, na onde está cada um dos nosso passos de forma resgistrada.
  
#	SLACK
* Foi nossa ferramenta de comunicação que facilitava a troca de informação entre o grupo e o Cliente, onde está documentada os nossos questionamentos permitindo que seja feita de forma agil e eficiente.
  
# Jira Software
* Foi nossa ferramenta de comunicação que facilitava a troca de informação entre o grupo e o Cliente, onde está documentada os nossos questionamentos permitindo que seja feita de forma agil e eficiente.



# Backlog do produto

## Sprint 1. Concepção
- [x] Defina o propósito da API;
- [x] Identifique os elementos principais;
- [x] Repositório no GITHUB;
- [x] Backlog do produto no jira software;
- [x] Banco de dados relacional;
- [x] Custo por KM;
- [x] Custo por unidade transportada;
- [x] Integrar banco de dados ao Power BI;
- [x] Apresentação e aprovação.

## Sprint 2. Atualização
- [x] Atualização do dashboard;
- [x] Melhor conversação entre o banco de dados e Power bi;
- [x] Adaptar gráficos do excel apresentados na sprint 1 para o Power bi;
- [x] Exploração de novos gráficos para melhor visualização;
- [x] Atualização do JIRA;
- [x] Atualização do GITHUB;
- [x] Atualização do relatório Sprint 2;
- [ ] Apresentação e aprovação.


## Dashboard no Power BI
Utilizando a ferramenta Power BI desenvolvemos e nos desafiamos montando um dashboard mostrando resultados que adquirimos durante o projeto desenvolvendo algo que seja compreensível e de facil visualização.
  
# Competências desenvolvidas

## Hard Skill (saber tecnológico)
<details>
<summary>Hard Skills desenvolvidas</summary>
  
| Tecnologia/Metodologia | Classificação |
| ---------------------- | ------------- |
| GitHub | ★ ★ ★ ★ ☆ ☆ ☆ ☆ ☆ ☆ |
| Gestão de Projetos | ★ ★ ★ ★ ★ ☆ ☆ ☆ ☆ ☆ |
| Scrum Master | ★ ★ ★ ★ ☆ ☆ ☆ ☆ ☆ ☆ |
| Prodct Owner | ★ ★ ★ ★ ★ ☆ ☆ ☆ ☆ ☆ |
| Markdown | ★ ★ ★ ★ ★ ☆ ☆ ☆ ☆ ☆ |
| Git Projects | ★ ★ ★ ☆ ☆ ☆ ☆ ☆ ☆ ☆ |
 
</details>

## Soft Skill (saber comportamental)
<details>
<summary>Soft Skills desenvolvidas</summary>

| Habilidades | Classificação |
| ---------------------- | ------------- |
| Colaboração | ★ ★ ★ ★ ★ ☆ ☆ ☆ ☆ ☆ |
| Proatividade| ★ ★ ★ ★ ★ ★ ☆ ☆ ☆ ☆ |
| Pensamento Crítico | ★ ★ ★ ★ ☆ ☆ ☆ ☆ ☆ ☆ |
| Gerenciamento de Tempo | ★ ★ ★ ☆ ☆ ☆ ☆ ☆ ☆ ☆ |
| Adaptabilidade | ★ ★ ★ ★ ★ ☆ ☆ ☆ ☆ ☆ |
| Resiliência | ★ ★ ★ ★ ★ ★ ★ ☆ ☆ ☆ |

</details>

# Autores
|    Função     | Nome                                  |                                                                                                                                                      LinkedIn & GitHub                                                                                                                                                      |
| :-----------: | :------------------------------------ | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| Product Owner |   Luiz Gustavo     |     [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/luiz-gustavo-) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/JoaoM-py)              |
| Scrum Master  | Cristovão Ferreira  |      [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/jhonathan-oliveira-) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/MariaGabrielaReis)     |
| Team Member   | Ricardo Henrique        |        [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/jhonathan-oliveira-) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://www.linkedin.com/in/ricardo-henrique-de-medeiros-siqueira-04a2b0263/)     |
