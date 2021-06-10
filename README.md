# Integração entre WA + api do telegram + Node-Red
Created for toolchain: https://cloud.ibm.com/devops/toolchains/1a106474-38bb-4c49-9b2f-ba25d2a05fa1?env_id=ibm:yp:us-south
criando um fluxo no nodeRed integrando o watson assitant com a api do telegram 

CURSO SUPERIOR DE TECNOLOGIA EM ANÁLISE E DESENVOLVIMENTO DE SISTEMAS ATIVIDADE AVALIATIVA 
DISCIPLINA: AI & CHATBOT ANO: 2021


CHECKPOINT 1 - TESTE DE TURING CINÉFILO


Suponha que  você  teve  um  problema e  quer  resolvê-lo apenas digitando, e resolve entrar  em  contato com  serviço do  SAC de  uma   empresa. Alguém te atende, resolve  seu  problema  e   no   ﬁm  da   conversa  há   um   formulário  para   avaliar   o atendimento.  Em  uma   das perguntas do  formulário de  atendimento há  a  seguinte questão:



“Você acha que foi atendido  por um ser humano ou uma máquina?”



Suponha que  você  responda foi atendido por um ser humano, mas na realidade o  tempo  todo   era  uma   máquina  ou  agente conversacional  falando  contigo.  Esse agente acabou de passar no famoso Teste de Turing!!



Como assim? O que é isso? De onde vem isso?



Em  1950,  o  cientista  considerado  pai  da  computação,  publica   um  trabalho muito  importante, inclusive atualmente, com  o título “Computing machinery  and intelligence” (em  português Maquinário da  computação e inteligência) onde  ele faz a seguinte indagação:



“As máquinas podem  pensar?”



Quando   um   agente conversacional  tem   capacidade  de  simular comportamentos humanos sem  ser  distinguido  de  um  ser humano,  tal  máquina acabou de passar pelo Teste de Turing, e isso ﬁcou conhecido popularmente como “O Jogo da Imitação”.



E o que eu, aluno da FIAP, tenho a ver com isso tudo?



Dentre   algumas  das tecnologias  mais  utilizadas  pelo  mercado de  trabalho estão os agentes conversacionais,  e  nós que  estamos interessados  em  aprender, desenvolver  e  aplicá-los  para   estarmos  aptos  para   trabalhar  e  construir  bons e humanizados  agentes,  temos que  colocar  em  prática  nosso conhecimento  e provar que sabemos fazer.


Sendo  assim, sua missão nesse trabalho será criar um agente conversacional usando as ferramentas apresentadas em aula  que  passe em uma  versão simpliﬁcada do  Teste de  Turing, que  iremos chamar de  Teste de  Turing  Cinéﬁlo.  Neste teste, o computador deverá se passar por  algum  personagem do cinema, personagens estes escolhidos por vocês.

No  ﬁnal  desse  semestre vocês entregarão um  Telegram do  seu personagem escolhido funcionando que deverá nos convencer de que é o personagem de verdade e não  uma  máquina,  sendo assim  façam a escolha  do  personagem conscientemente, pois não poderá ser mudada.

A conclusão do  semestre é  ter  um  agente conversacional criado, revisado e integrado  por  vocês usando os  checkpoints  como sprints  de  um  projeto   ﬁnal  do semestre, ou seja, cada pedaço é extremamente importante. Legal né!?!?



O que será avaliado?


A avaliação será baseada na profundidade do conhecimento prático e, obviamente, o quanto seu personagem se parece com o personagem real.

Além disso, a compreensão sobre intenções e entidades devem ser claras, bem como a  aplicação da  técnica de  construção de  diálogos utilizando as boas práticas apresentadas ao longo  do curso para  sempre otimizar  a experiência que o usuário terá ao conversar com o personagem.



Quem fará?


O trabalho poderá ser feito individualmente ou em dupla 2, não recomendamos fazê-lo individualmente, pois é muito  importante discutirem, testarem e chegarem em um consenso sobre o trabalho.

A experiência  com  grupos maiores  é que  nem  todo  mundo executa e isso  é muito   importante  para   a   próxima   etapa  desse  trabalho  que   será  sequencial  e cumulativo, como citado anteriormente.



O que precisa ser implementado?


De acordo com  os temas e personagens escolhidos por vocês, chegamos a seguinte lista de personagens elegíveis:


PERSONAGENS Batman (Bruce Wayne)
Coringa

Homem de Ferro (Tony Stark) Harry Potter
Naruto

Mulher Maravilha (Diana)



Vocês deverão escolher um personagem dentre os 6 mais votados que estão na tabela acima para  criar e personiﬁcar o personagem que  passará no Teste de Turing Cinéﬁlo do 1TDS-2021.

A implementação da capacidade de entender e responder via texto do seu personagem escolhido deverá ser feita através do serviço Watson Assistant da IBM.

Para  garantir  que  seu personagem passe no nosso Teste de Turing (e quem  sabe no
Teste de Turing real), você pode  se guiar pelos seguintes cenários:


1.   Cenários:

●   Personagem deve apresentar-se e induzir a continuidade da conversa;

●   Personagem deve convencer com estilo de fala (Jargão, por exemplo) que o personagem é de verdade;

●   O  personagem  deve   induzir  o  usuário  a  fazer   alguma  pergunta  sobre especíﬁca sobre ele;

●   O personagem  deverá conseguir  responder com  conﬁança e  destreza a alguma pergunta especíﬁca induzida  no Cenário genérico;

●   O personagem deverá ser capaz de escapar de maneira inteligente e versátil de perguntas que não fazem sentido;




2.   Dicas e orientações:

Sabemos  que   é  extremamente  difícil  construir  um  agente/assistente  que  não  se pareça com  uma  máquina, mas é  possível fazer  isso para  uma  quantia limitada  de perguntas  e  com   alguma  indução  na  conversa (lembre-se  do  primeiro   chatbot,  o psicoterapeuta Eliza, que  fazia  mais perguntas do que  respostas - inclusive você pode testá-lo   em   inglês   aqui    https://web.njit.edu/~ronkowit/eliza.html)  .  A  seguir,   vão algumas dicas:

●   Testem com  o maior  número possível de pessoas - você  está fazendo um super-herói, o público infantil pode  ser um excelente público de teste;

●   Usem um número mínimo de frases por intenção;

●   Tenham uma quantia equilibrada de frases por intenção;

●   Abusem de entidades para  ajudar  na desambiguação;

●   Não criem diálogos com muitas camadas;

●   Variáveis  de  contexto podem tornar  seu personagem mais  inteligente  e a conversa parecerá mais humana.




