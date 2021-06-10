# Integração entre WA + Node-Red
Created for toolchain: https://cloud.ibm.com/devops/toolchains/1a106474-38bb-4c49-9b2f-ba25d2a05fa1?env_id=ibm:yp:us-south
criando um fluxo no nodeRed integrando o watson assitant ao um site que estamos construindo para a  disciplina de web.

CURSO SUPERIOR DE TECNOLOGIA EM ANÁLISE E DESENVOLVIMENTO DE SISTEMAS ATIVIDADE AVALIATIVA 
DISCIPLINA: AI & CHATBOT ANO: 2021


Este arquivo contém informações de um chatbot que se passa por um guia, dando dicas e informações pertinentes ao projeto multidisciplinar que estamos desenvolvendo na faculdade FIAP.

CURSO SUPERIOR DE TECNOLOGIA EM ANÁLISE E DESENVOLVIMENTO DE SISTEMAS DOCUMENTO PARA A CHALLENGE
TURMA: 1º. TDS – “A, F, G, H, J, R e S” ANO: 2021


1.  Objetivo

Capacitar o aluno a desenvolver um projeto, simulando a experiência profissional, utilizando técnicas, ferramentas, metodologias e boas práticas trabalhadas ao longo do curso de tecnologia.


2.  Normas Básicas

1.  Números de integrantes por grupo: até 6 alunos

2.  Não será permitido o desenvolvimento individual do projeto.

3.  Os grupos têm obrigação de aceitar novos componentes.

4.  Os componentes dos grupos, através do líder, poderão indicar a não atribuição da nota aos componentes do grupo que não participaram das atividades relativas ao projeto.
5.  Os grupos devem idealizar os projetos a serem desenvolvidos ao longo do ano letivo, dividido em entregas parciais durante o 1º. e 2º. semestre.
6.  As entregas serão parciais e divididas entre as disciplinas trabalhadas ao longo do ano. As solicitações são individuais, ou seja, feitas por cada disciplina.
7.  Será realizada uma entrega ao final de cada sprint, a entrega deve conter todos os pedidos de todas as disciplinas.

3.  Responsabilidades


Responsabilidades dos alunos

•  Ter ciência do documento da Challenge e cumprir as entregas conforme solicitação dos professores.
•   Todos os componentes do grupo devem estar envolvidos em todas as disciplinas do projeto. Fica proibido e irá onerar a nota individual do aluno que desenvolver o conteúdo somente de uma das disciplinas, todos os alunos devem gerar artefatos de todas as disciplinas.
•   Atentar-se a qualidade no desenvolvimento dos entregáveis.


Responsabilidades dos Professores do Curso

•   Responsáveis por orientar o desenvolvimento do projeto em suas disciplinas.

•   A correção de cada entregável, é de responsabilidade do professor da disciplina em cada turma.
•   Disponibilizar nota individual referente à disciplina.



1/4
CURSO SUPERIOR DE TECNOLOGIA EM ANÁLISE E DESENVOLVIMENTO DE SISTEMAS DOCUMENTO PARA A CHALLENGE
TURMA: 1º. TDS – “A, F, G, H, J, R e S” ANO: 2021


•   Manter   informações   no   grupo   de   professores   relativas   a   cada   grupo

(compartilhar avaliação dos grupos)

•   Manter  sua  solicitação  de  entrega  sempre  atualizada  para  o  grupo  de professores e alunos.
•   Explicar detalhadamente entregável da disciplina e critérios de avaliação junto aos alunos
•   Disponibilizar justificativa de nota aplicada ao grupo/aluno, quando se aplicar.



Relação de professores responsáveis pela Challenge:

•   1 TDS A, F, G, H, J, R e S

Professores Allen Fernando e José Henrique Cordeiro, gestão, planejamento e acompanhamento dos projetos.

Professores Fernanda Caetano e José Henrique Cordeiro, scrum master, comunicação e orientação de entregas junto à IBM.

Demais  professores  do  curso,  mentoria  e  acompanhamento  técnico  dos projetos.


4.  Exigências a serem cumpridas em cada disciplina



4.1. AI & Chatbot

•    1ª Entrega: Um documento PDF

Descrição da solução proposta pelo grupo para o desafio (Challenge).

Descrição de como agentes conversacionais podem auxiliar na solução do projeto.
Descrição de uma proposta de solução um problema usando o Watson

Assistant como parte da solução do desafio.

Essa entrega será apenas escrita, ou seja, em formato PDF.



•   2ª Entrega: O arquivo JSON do Watson Assistant

o Definição de 5 intenções e seus respectivos exemplos:

Explicar o propósito da definição de cada intenção proposta na própria descrição do Watson Assistant.
Cada intenção deverá contar um mínimo de 15 exemplos.

o Não serão contabilizadas intenções de saudações e despedidas.


2/4
CURSO SUPERIOR DE TECNOLOGIA EM ANÁLISE E DESENVOLVIMENTO DE SISTEMAS DOCUMENTO PARA A CHALLENGE
TURMA: 1º. TDS – “A, F, G, H, J, R e S” ANO: 2021


Definição de 3 entidades e seus respectivos sinônimos:

Explicar o propósito da definição de cada entidade proposta na própria descrição do Watson Assistant.
Cada entidade deve conter pelo menos 3 sinônimos.

Não serão aceitas entidades do tipo "sim", "não" e "ok".

Essa entrega será composta apenas pelo JSON do Watson Assistant.


4.2. Agile Software Design

•   1ª Entrega:

Termo de Abertura de Projeto (TAP), contendo:

▪   Justificativa e Objetivo do Projeto (entendimento do problema)

▪   Escopo do Projeto (delimitação do escopo e interações)

▪   Premissas identificadas

▪   Escopo preliminar do produto/solução

▪   Cronograma das atividades previstas para o primeiro semestre

(da ativação do projeto até a 2ª entrega)

▪   Equipe envolvida

▪   Restrições e Riscos

Os ítens Escopo do Projeto e Escopo do Produto deverão seguir padrão que será apresentado oportunamente pelos professores.
•   2ª Entrega:

Backlog do projeto (contexto funcional) contendo:

▪   Estórias do Usuário

▪   Diagrama de Caso de Uso formalizando o escopo do produto

▪   Planejamento de Sprints (atividades até a entrega final)



4.3. Computational Thinking using Python

•   Não haverá entregas no 1º. semestre.


4.4. Database Modeling & SQL

•   1ª Entrega:

Descrever o objetivo da solução definida pelo grupo e quais são as informações necessárias a persistir.
o Relação das principais entidades e atributos necessários para a

solução proposta.




3/4
CURSO SUPERIOR DE TECNOLOGIA EM ANÁLISE E DESENVOLVIMENTO DE SISTEMAS DOCUMENTO PARA A CHALLENGE
TURMA: 1º. TDS – “A, F, G, H, J, R e S” ANO: 2021


•   2ª Entrega:

A Relação das entidades e atributos propostos revisados na primeira entrega. Definição de chave primária para cada entidade proposta, descrição dos atributos propostos, informando: atributos compostos e multivalorados e a indicação do conteúdo a ser armazenado (texto, número ou data).
o Modelo entidade relacionamento preliminar: contendo entidades e atributos, chave primária e indicação de atributos opcionais e mandatórios.


4.5. Domain Driven Design

•   1ª Entrega:

Modelagem das classes do projeto.

•   2ª Entrega:

Criação do projeto Java com as classes e atributos de cada.

Construtores, getters e setters.

uma classe principal com o teste das demais.


4.6. Responsive Web Development

•   1ª Entrega:

Organograma com o fluxo de navegação do sistema:

▪   Uma  apresentação(pptx)  onde  seja  possível  enxergar  a navegação  do  sistema  como  um  todo,  descrevendo  a
funcionalidade de cada página.

•   2ª Entrega:

Telas do Sistema (navegável):

▪   Criar as telas do sistema de forma que seja possível enxergar as funcionalidades e a integração entre cada uma delas. As telas devem ser criadas em HTML5/CSS3/JS e BOOTSTRAP.


5.  Entregas primeiro semestre

•   1ª Entrega: 04/04/2021 – Via portal do Aluno

•   2ª Entrega: 16/05/2021 - Via portal do Aluno


