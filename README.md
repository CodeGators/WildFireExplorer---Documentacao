# 🚀 Propósito do Projeto

Este projeto foi desenvolvido pelos alunos do 2º DSM da Fatec Jacareí com o objetivo de criar uma aplicação web que permite aos usuários acessar informações sobre áreas queimadas, riscos de incêndio e focos de calor, utilizando dados do Programa Queimadas do INPE. A ferramenta busca facilitar o acesso a esses importantes dados ambientais, contribuindo para o monitoramento e a prevenção de incêndios no território brasileiro.

## 🌟 Visão Geral do Projeto

Este repositório visa **centralizar e organizar a documentação do time** para garantir a transparência, a comunicação e o alinhamento contínuo durante o ciclo de vida do projeto. Os documentos são **atualizados regularly** para refletir as mudanças no escopo, nas metas de desenvolvimento e nas sprints.

🔍 **Aqui você encontrará:**
- Visão geral do projeto.
- Detalhamento das funcionalidades.
- Planejamento e progresso das sprints.

## 📂 Índice

1. [Product Backlog](Backlog/BackLog%20-%20V2.docx)
2. [Visual](Visual/)
3. [UML](Uml/)
4. [Reuniões](Reuni%C3%A3o/)
5. [Burndown](Burndown/)
6. [Documentação de Testes](Documentacao/)

## ⚠️ Observação

Este repositório tem como objetivo documentar todo o nosso projeto em desenvolvimento. Caso você queira acompanhar o progresso do nosso sistema, acesse o [repositório do servidor aqui](https://github.com/CodeGators/CodeGators---Front-Server), onde estão disponíveis todos os arquivos do código-fonte.

---

# 🛠 PRODUCT BACKLOG

### Requisitos Funcionais

<table>
    <tr>
        <th>REQUISITO FUNCIONAL</th>
        <th>USER STORIES</th> 
    </tr>
    <tr>
        <td>RF.01</td>
        <td>Como usuário do site, quero ter acesso ao banco de dados para visualizar o histórico das queimadas em determinados períodos de tempo;</td>
    </tr>
    <tr>
        <td>RF.02</td>
        <td>Como professor de Engenharia de Software, gostaria de visualizar os diagramas UML a fim de entender a modelagem do projeto;</td>
    </tr>
    <tr>
        <td>RF.03</td>
        <td>Como usuário, gostaria de consultar os focos de calor por estado para fins de pesquisa;</td>
    </tr>
    <tr>
        <td>RF.04</td>
        <td>Como usuário do site, gostaria de consultar os focos de calor por bioma para fins de pesquisa;</td>
    </tr>
    <tr>
        <td>RF.05</td>
        <td>Como usuário do site, gostaria de consultar o risco de fogo por estado para fins de pesquisa;</td>
    </tr>
    <tr>
        <td>RF.06</td>
        <td>Como usuário do site, gostaria de consultar o risco de fogo por bioma para fins de pesquisa;</td>
    </tr>
    <tr>
        <td>RF.07</td>
        <td>Como usuário do site, gostaria de consultar as áreas queimadas por estado para fins de pesquisa;</td>
    </tr>
    <tr>
        <td>RF.08</td>
        <td>Como usuário do site, gostaria de consultar as áreas queimadas por bioma para fins de pesquisa;</td>
    </tr>
    <tr>
        <td>RF.09</td>
        <td>Como usuário do site, gostaria de visualizar gráficos de focos de calor por estado e bioma para fins de pesquisa;</td>
    </tr>
    <tr>
        <td>RF.10</td>
        <td>Como usuário do site, gostaria de visualizar gráficos de risco de fogo por estado e bioma para fins de pesquisa;</td>
    </tr>
    <tr>
        <td>RF.11</td>
        <td>Como usuário do site, gostaria de visualizar gráficos de área queimada por estado e bioma para fins de pesquisa;</td>
    </tr>
    <tr>
        <td>RF.12</td>
        <td>Como usuário do site, quero fazer consultas por intervalo de tempo para fins de pesquisa;</td>
    </tr>
    <tr>
        <td>RF.13</td>
        <td>Como usuário do site, quero interagir respondendo a duas perguntas para fins de fixação de conhecimento;</td>
    </tr>
    <tr>
        <td>RF.14</td>
        <td>Como membro da equipe, quero criar a documentação dos casos de teste para garantir a qualidade do sistema.</td>
    </tr>
</table>

---

## Equipe

<table>
    <tr>
        <th>Função</th>
        <th>Nome</th>
        <th>GitHub</th>
    </tr>
    <tr>
        <td>Scrum Master</td>
        <td>Stefan Souza Cruz</td>
        <td><a href="https://github.com/Stefan0212"><img src="imagens/github-logo.png" style="height:20px; width:20px;" alt="GitHub"></a></td>
    </tr>
    <tr>
        <td>Product Owner</td>
        <td>Arthur Augusto Da Silva Cunha</td> 
        <td><a href="https://github.com/ArthurAugusto10"><img src="imagens/github-logo.png" style="height:20px; width:20px;" alt="GitHub"></a></td>
    </tr>
    <tr>
        <td>Developer</td>
        <td>Gustavo Reis</td>
        <td><a href="https://github.com/GustavoReis-xml"><img src="imagens/github-logo.png" style="height:20px; width:20px;" alt="GitHub"></a></td>
    </tr>
    <tr>
        <td>Developer</td>
        <td>Filippe Gonçalves Marchezoni</td>
        <td><a href="https://github.com/FilippeGM"><img src="imagens/github-logo.png" style="height:20px; width:20px;" alt="GitHub"></a></td>
    </tr>
    <tr>
        <td>Developer</td>
        <td>Anderson Fontes</td>
        <td><a href="https://github.com/Anderson-Fontes"><img src="imagens/github-logo.png" style="height:20px; width:20px;" alt="GitHub"></a></td>
    </tr>
    <tr>
        <td>Developer</td>
        <td>Rafael Shinji Tomokame</td>
        <td><a href="https://github.com/RafaelShinjiTomokame"><img src="imagens/github-logo.png" style="height:20px; width:20px;" alt="GitHub"></a></td>
    </tr>
</table>

---

# SPRINT 1

Na primeira sprint, nosso principal objetivo foi criar o banco de dados do nosso site e a prototipagem visual utilizando a ferramenta Figma. Para alcançar esse objetivo, dividimos a nossa equipe de acordo com o nível de prioridade de cada tarefa, entendendo que a maior prioridade era estruturar e disponibilizar o ambiente do banco de dados. O Scrum Master monitorou periodicamente o gráfico de *burndown* e, durante as reuniões diárias, alinhou com a equipe o andamento das atividades. Buscamos atender a todos os requisitos levantados pelo Product Owner e validados por ele.

### Sprint Backlog

<table>
    <tr>
        <th>REFERÊNCIA</th>
        <th>REQUISITO DA SPRINT</th>
        <th>RESPONSÁVEL</th>
        <th>CONCLUÍDA</th>
    </tr>
    <tr>
        <td>RF.01</td>
        <td>Criar ambiente do banco de dados</td>
        <td>Stefan, Anderson, Arthur</td>
        <td>✔</td>
    </tr>
    <tr>
        <td>RF.02</td>
        <td>Criar os diagramas solicitados pelo professor</td>
        <td>Arthur</td>
        <td>✔</td>
    </tr>
    <tr>
        <td>RF.03</td>
        <td>Fazer a consulta geoespacial</td>
        <td>Gustavo, Anderson</td>
        <td>✔</td>
    </tr>
</table>

### Burndown

![Burndown Sprint 1](https://github.com/CodeGators/CodeGators---Documentacao/blob/main/imagens/sprint1.png)

### Sprint Retrospective

Nesta primeira sprint, enfrentamos algumas dificuldades iniciais relacionadas à divisão de tarefas, atribuição de responsabilidades e desafios técnicos no uso de ferramentas como PostGIS e pgAdmin.
Entre os pontos positivos, destacamos a comunicação eficiente e o bom entrosamento do time, o que proporcionou um ambiente de trabalho produtivo. Uma iniciativa marcante foi a realização de reuniões além do horário acadêmico, o que permitiu melhor organização e alinhamento entre os membros.

---

# SPRINT 2

Durante a segunda sprint, aprimoramos a estrutura do banco de dados e otimizamos a conexão com o backend, garantindo maior eficiência nas consultas. O frontend foi refinado com melhorias visuais e de usabilidade. Implementamos a visualização de focos de calor diretamente no mapa, facilitando a análise espacial dos dados, além de incluir um gráfico interativo que exibe os focos de calor por estado. Esses avanços fortaleceram a integração entre as camadas do sistema e ampliaram as funcionalidades da aplicação.

### Sprint Backlog

<table>
    <tr>
        <th>REFERÊNCIA</th>
        <th>REQUISITO DA SPRINT</th>
        <th>RESPONSÁVEL</th>
        <th>CONCLUÍDA</th>
    </tr>
    <tr>
        <td>RF.01</td>
        <td>FAZER A CRIAÇÃO DO SISTEMA</td>
        <td>Stefan, Anderson</td>
        <td>✔</td>
    </tr>
    <tr>
        <td>RF.02</td>
        <td>CONEXÃO COM O BANCO DE DADOS</td>
        <td>Arthur, Gustavo</td>
        <td>✔</td>
    </tr>
    <tr>
        <td>RF.03</td>
        <td>DIAGRAMA DE SEQUÊNCIA</td>
        <td>Rafael</td>
        <td>✔</td>
    </tr>
</table>

### Burndown

![Burndown Sprint 2](https://github.com/user-attachments/assets/46ec3eb0-d596-4818-825f-bdc2f0d1f46e)

### Sprint Retrospective

Nesta segunda sprint, tivemos um desempenho bastante satisfatório em comparação com a anterior. Evoluímos significativamente na organização e na gestão do projeto, com avanços notáveis na definição de tarefas e na priorização das entregas. Durante o período, enfrentamos alguns desafios interpessoais na equipe, porém conseguimos resolvê-los de maneira eficaz, sem impactar o progresso do desenvolvimento.

---

# SPRINT 3

Nesta última sprint, nosso foco foi implementar as funcionalidades de área queimada e focos de calor, além de estruturar a seção onde os gráficos são gerados. Trabalhamos para garantir que os dados apresentados estivessem coerentes com as informações exibidas no mapa, validando as entradas e saídas do sistema. Também dedicamos atenção à melhoria visual da interface, buscando torná-la mais intuitiva, e realizamos ajustes de desempenho para tornar a aplicação mais ágil e eficiente.

### Sprint Backlog

<table>
    <tr>
        <th>REFERÊNCIA</th>
        <th>REQUISITO DA SPRINT</th>
        <th>RESPONSÁVEL</th>
        <th>CONCLUÍDA</th>
    </tr>
    <tr>
        <td>RF.01</td>
        <td>ALGORITMO RECURSIVO</td>
        <td>Anderson, Gustavo</td>
        <td>✔</td>
    </tr>
    <tr>
        <td>RF.02</td>
        <td>APLICAR OS DADOS</td>
        <td>Gustavo</td>
        <td>✔</td>
    </tr>
    <tr>
        <td>RF.03</td>
        <td>ESTILIZAR INTERFACE</td>
        <td>Anderson</td>
        <td>✔</td>
    </tr>
    <tr>
        <td>RF.04</td>
        <td>ROTAS</td>
        <td>Gustavo</td>
        <td>✔</td>
    </tr>
    <tr>
        <td>RF.05</td>
        <td>CRIAR GRÁFICOS</td>
        <td>Anderson, Gustavo</td>
        <td>✔</td>
    </tr>
</table>

### Burndown

![Burndown Sprint 3](https://github.com/CodeGators/CodeGators---Documentacao/blob/main/imagens/sprint3.png)

### Sprint Retrospective

A sprint foi, de forma geral, bastante produtiva. A equipe demonstrou proatividade, boa comunicação e cooperação, o que facilitou o cumprimento das atividades e fortaleceu o trabalho em equipe. As reuniões de alinhamento contribuíram para uma gestão de tarefas mais clara, e o comprometimento da maioria dos integrantes possibilitou um bom ritmo de desenvolvimento e aprendizado coletivo. No entanto, também enfrentamos pontos de atenção, como oscilações no engajamento de alguns membros, descumprimento de prazos e certas dúvidas de direcionamento em momentos-chave do projeto. Esses desafios evidenciaram a importância de manter todos alinhados desde o início da sprint e de reforçar a responsabilidade individual para os próximos projetos.