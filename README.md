# Estudo de caso: Informatizar o setor do CEUA (Comitê de Ética no Uso de Animais).
<p align="center">
  <img src="https://github.com/Arthur0020/Projeto_integrador_NUPEX/assets/131721376/52baf8e3-896e-45cc-be2c-d746ad65a993" alt="Texto Alternativo">
</p>
<p align="center">Figura 1 - Logo do SICEUA</p>

# Visão geral
## O Desafio
O desafio central é evoluir o projeto do sistema, que está atualmente em uma fase pré-pronta, para um estágio de desenvolvimento completo e funcional. Para isso, é necessário:

- Refinar os Requisitos: Realizar uma análise minuciosa das necessidades e especificações atuais, garantindo que todas as funcionalidades essenciais sejam incorporadas no novo sistema. Isso envolve a tradução de requisitos de alto nível para especificações técnicas detalhadas, que orientarão o desenvolvimento do software.

- Aprimorar o Protótipo: O protótipo existente deve ser refinado e aprimorado para assegurar que ele atenda aos padrões de usabilidade e funcionalidade exigidos pelos usuários finais. Isso inclui a realização de testes de usabilidade, a incorporação de feedback dos stakeholders e a implementação de melhorias iterativas para garantir que o protótipo evolua para uma versão pronta para o desenvolvimento completo.

- Garantir a Continuidade e Evolução do Projeto: O projeto deve continuar evoluindo, acompanhando as mudanças nas necessidades dos usuários e incorporando novas funcionalidades que possam surgir ao longo do tempo. Isso inclui o planejamento de um roadmap de desenvolvimento, a definição de milestones e a alocação de recursos necessários para garantir a entrega contínua de valor ao CEUA.

Em resumo, o desafio neste cenário é garantir que todas as análises e documentações necessárias sejam realizadas de forma precisa e eficiente, que o protótipo seja devidamente aprimorado para estar pronto para o desenvolvimento, e que o projeto continue evoluindo de maneira a atender às necessidades dinâmicas do CEUA.

## Contexto
Atualmente o CEUA não possui um sistema digital para realizar suas atividades de avaliações de projetos envolvendo o uso de animais, sendo todos feitos manualmente, o que acaba por tornar todo o processo bem trabalhoso e passível de possíveis falhas, além de acabar perdendo tempo com pequenos detalhes e deta forma tornando-se não muito efetivo para os usuários. 
Existem diversas melhorias que podem ser realizadas no atual método usado pelo CEUA para que ele se torne apropriado para seus usuários finais, de tal forma com que aumente a produtividade e efetividade.

# Ciclo de vida
## Ciclo de vida Estrela
O modelo estrela representa o ciclo de vida do desenvolvimento de software, focando em uma abordagem iterativa e centrada no usuário, dando ênfase na flexibilidade e na capacidade de adaptação às necessidades e feedback dos usuários durante todo o processo de desenvolvimento. É um modelo especialmente útil em projetos onde os requisitos podem mudar com frequência ou onde a validação contínua com o usuário é crucial para o sucesso do sistema. Ele promove um desenvolvimento ágil e adaptativo, alinhando as práticas modernas de engenharia de software e desenvolvimento centrado no usuário.

<p align="center">
  <img src="https://github.com/Arthur0020/Projeto_integrador_NUPEX/assets/163935730/c12987ce-5714-4ff3-89fd-2475e1805ace" alt="Modelo Estrela">
  </p>
<p align="center">Figura 2 - Ciclo de Vida Estrela</p>

# Análise de tarefas usuários e função
## Why?
### Quem utilizará o sistema?
Neste primeiro momento de reflexão, não conseguimos pensar nas pessoas que fariam o uso direto do sistema, porém em uma reunião com a coordenadora do CEUA foi nos passado a seguinte divisão dos possíveis usuários: 
Professores, Pós-graduandos, Secretária, Pareceristas e Coordenadores.

### Quais seriam os problemas?
- Envio do formulário mesmo quando ele não está com todas informações necessárias preenchidas;
- Pelo processo ser manual, a triagem entre a secretaria e os pareceristas (avaliadores de projetos) não funciona da maneira desejada;
- Processo completamente manual, desde o preenchimento dos formulários, a triagem entre os processos a serem analisados, a analise de cada projeto e aprovação/reprovação e a comunicação entre as partes envolvidas;

### Descrição do cenário e interação atual
No atual cenário do projeto, o protótipo realizado com base nos requisitos de alto nível é capaz de executar todas as principais interações previstas nas documentações de requisitos como: 
- Um menu de opções no cabeçalho que dão acesso as funcionalidades requeridas no documento de requisitos.
- Uma funcionalidade de login focada nos três diferentes níveis de acesso especificados no documento de requisitos: Login para pareceristas, login para triagem e login para o responsável do projeto.
- Um formulário padrão de uso de animais e um formulário para uso de amostras biológicas para o cadastro de projetos, ambos com a representação de preenchimento obrigatório.
- Dentro dos formulários há a representação para anexar documentos extras necessários, que também possuem o anexo obrigatório.
- Os formularios possuem a representaçao de formas de preenchimento, sendo elas, a marcação de caixas de seleção e a inclusão de texto descritivo.
- O protótipo possui a representação do status do projeto para o acompanhamento.
- Pensado exclusivamente para utilização web em computadores.

### Analise de Tarefas
#### Analise Hierárquica de tarefas
A análise hierárquica de tarefas (AHT) é uma técnica fundamental utilizada no campo da engenharia de software e da ergonomia para compreender e decompor as tarefas realizadas por usuários ao interagirem com um sistema. Este documento de AHT tem como objetivo mapear de maneira detalhada e estruturada todas as atividades que um usuário precisa realizar para alcançar objetivos específicos dentro de um sistema de software.

Ao descrever e organizar as tarefas em uma hierarquia, a AHT facilita a identificação das principais ações e decisões envolvidas no uso do sistema. Cada tarefa é decomposta em subtarefas menores e mais manejáveis, permitindo uma análise minuciosa de cada passo necessário para completar uma ação. Esta abordagem hierárquica não só ajuda a visualizar a complexidade e a sequência das atividades, mas também destaca as interdependências entre diferentes tarefas.

- [Link para acessar o documento de Análise hierárquica de tarefas do SICEUA](https://drive.google.com/file/d/1i9QRQ80H8oWBMSoweJsZeOTSfryrzGLp/view)(Conforme introduzido o conceito de um documento de Análise hierárquica de tarefas, este é um diagrama com a hierarquia de tarefas que o SICEUA possue e que os usuários conseguem utilizar).

  
## Storytelling
"Em um dia comum na vida da Professora Clara, uma das responsáveis pelo Comitê de Ética no Uso de Animais da UNIVIÇOSA, uma situação rotineira tomou um rumo inesperado. Ela se deparou, mais uma vez, com o recebimento de um formulário incompleto por um dos Pós-graduandos. Isso não era novidade, mas agravava a eficiência de todo o processo, consumindo tempo em correções e atrasando aprovações.
Os dias se arrastavam com o mesmo padrão. A Secretária, sempre atarefada, era a mediadora dos pareceres, recebendo formulários, repassando a pareceristas, realizando as correções e submetendo ao Comitê. No entanto, o processo esbarrava na lentidão da realização dos passos de forma manual, até então o atual processo usado, cujo não facilitava a comunicação entre os envolvidos e consumia muito tempo e disponibilidade dos pareceristas.
Foi durante um reuniãocom os coordenadores que a necessidade de mudança se tornou mais evidente. Era crucial compreender que, para melhorar, precisavam entender quem, de fato, utilizaria o sistema. Os Professores, os Pós-graduandos, a Secretária, os Pareceristas e Coordenadores estavam na linha de frente, mas o atual método utilizado não atendia às suas necessidades de forma eficaz.
O problema ia além do envio de formulários incompletos. Não existia um sistema de hierarquia, dificultando o acesso de diferentes usuários e dificultando a questão da privacidade em relação a qual projeto foi avaliado por qual parecerista e a relação de projetos aprovados ou reprovados,não existia uma interface, afinal o processo era feito de forma manual, dificultando a comunicabilidade, o que ocasionava ruídos na comunicação e entendimento das etapas do processo.
Contudo, assim como em muitas histórias, esse impasse encontrou sua solução. Durante uma conferência sobre inovação em sistemas acadêmicos, a Professora Clara teve contato com uma nova abordagem. Ela descobriu um sistema revolucionário: um software que simplificava todo o processo e o tornava completamente digital.
Esse novo sistema prometia transformar a dinâmica do Comitê. Permitia o preenchimento progressivo dos formulários, garantindo que apenas dados completos fossem enviados, poupando tempo da Secretária. Além disso, a questão de hierarquia foi solucionada com a implementação de login e senha, proporcionando uma experiência personalizada para cada tipo de usuário.
A interface, agora intuitiva e comunicativa, ajudava na compreensão das etapas do processo, reduzindo erros e acelerando as aprovações. O sistema, finalmente, se alinhava às necessidades dos envolvidos.
Da frustração à eficiência, a Professora Clara e sua equipe passaram a utilizar o SICEUA (Sistema de Informatização da Comissão de Ética no Uso de Animais), um sistema que não só resolveu os problemas preexistentes, mas também simplificou e agilizou todo o processo. De formulários completos a uma interface acessível, a evolução do sistema trouxe um novo fôlego ao Comitê de Ética, tornando-o um ambiente mais produtivo e eficaz para todos os usuários."
Essa narrativa demonstra como a implementação de um novo sistema pode transformar um processo burocrático e moroso em algo mais eficiente e produtivo, atendendo às necessidades e frustrações dos usuários finais.

# WHO - Analise dos Stakeholders

## Personas
Com base nas hipóteses, storytelling e pesquisa com usuários, as personas foram criadas para representar os usuários que irão utilizar o produto:

<p align="center">
  <img src="https://github.com/Arthur0020/Projeto_integrador_NUPEX/assets/131721376/b272d6c3-112c-4be9-bace-66071aa0e15e" alt="Persona Miguel Almeida">
</p>  
<p align="center">Figura 4 - Persona do Miguel Almeida</p>

<p align="center">
  <img src="https://github.com/Arthur0020/Projeto_integrador_NUPEX/assets/131721376/bd56f1a8-6e96-42c9-a559-0bf2ab1c71f5" alt="Persona Clara Souza">
</p>
<p align="center">Figura 3- Persona da Clara Souza</p>


## Mapa de empatia
Com o intuito de entender as necessidades e as dores dos usuários, se colocando no lugar dele, foi desenvolvido um mapa de empatia considerando as personas que foram criadas.

### Mapas de empatia
<p align="center">
  <img src="https://github.com/Arthur0020/Projeto_integrador_NUPEX/assets/131721376/0febe0b1-bd56-49d1-bfd5-afd17682c97f" alt="Mapa de empatia Miguel">
</p>  
<p align="center">Figura 5 - Mapa de Empatia do Miguel Almeida</p>

<p align="center">
  <img src="https://github.com/Arthur0020/Projeto_integrador_NUPEX/assets/131721376/78ba9dee-1c81-4d20-a058-96a8a12393d1" alt="Mapa de empatia Clara">
</p> 
<p align="center">Figura 6 - Mapa de Empatia da Clara Souza</p>

## Avaliação - analise de tarefa usuários e função


# Engenharia de requisitos

## Elicitação de requisitos
A Elicitação de requisitos foi realizada através de uma reunião com a cliente que discorreu sobre os problemas que causavam o entrave no atual sistema de  submissão de projetos do CEUA, estes requisitos foram documentados a nível de usuário, ou seja, à um nível de explicação mais simples que a própria cliente consegue compreender.
- [Documento de requisitos a nível de Usuário](https://trello.com/c/WpOicLXP/34-requisitos-detalhados)

## Análise de requisitos
//Modelagem de ES - Pegar o modelo de diagrama e colocar aqui


## Especificação de requisitos
Foi realizado o refinamento dos requisitos que estavam a nível de usuário para o nível de sistema para auxiliar os programadores na etapa de desenvolvimento do sistema.
- [Documento de requisitos a nível de Sistema](https://trello.com/c/f9vPpcnA/25-documento-de-requisitos-refinados)

## Avaliação - Especificação de requisitos
### Validação de requisitos com o cliente
- A reunião realizada com a cliente foi ministrada no modelo workshop para validação de requisitos do protótipo e do sistema em si.
- Os participantes responsáveis pelo projeto fizeram perguntas para a cliente para validar se os requisitos gerais do sistema e do protótipo estavam de acordo com o que foi dito nas últimas reuniões.
- Foram citados os requisitos um a um para que a cliente pudesse validar ou discordar, assim como foi feita a apresentação do protótipo para que a cliente definisse o que estava dentro de suas expectativas e o que poderia melhorar. 
- A cliente deu sugestões de mudanças principalmente no protótipo para otimizar melhor a nevegabilidade e a usabilidade do sistema de forma que atenderia melhor a demanda.
- Foram anotados os requisitos abstraidos a partir das informações retiradas da reunião e foram realizados os trabalhos de refinamento destes novos requisitos para começar a readaptar o sistema e o projeto.

# Projeto conceitual e especificação do design
## Identidade visual
Para a identidade visual do sistema usamos a própria logo já utilizada pelo CEUA da UNIVIÇOSA e adaptamos o nome transformando-o em SICEUA (Sistema de Informatização do Comitê de Ética no Uso de Animais).

<p align="center">
  <img src="https://github.com/Arthur0020/Projeto_integrador_NUPEX/assets/131721376/5ababbae-fbc1-43fb-a57e-372d204157f3" alt="Identidade Visual">
</p> 
<p align="center">Figura 7 - Identidade Visual da Logo do SICEUA</p>

## Wireframe
Levando em consideração os requisitos funcionais e as referências que foram nos passadas pela coordenadora do CEUA, nós desenvolvemos um protótipo utilizando Wireframe da qual contém todas as funcionalidades cruciais idealizadas para que possam ser posteriormente prototipadas em alto nível.
- Na interface inicial do site é possível se acessar 4 funcionalidades principais com 2 subfuncionalidades cada uma que levam o usuário a diferentes interfaces de acordo com a escolha de determinada funcionalidade;
- Na interface inicial também se encontram as funcionalidades de login, da qual são divididas em 2 opções sendo a primeira o login para os pareceristas(analistas de projetos) e a segunda para a triagem de processos;
- O login dos pareceristas contará com usuário e senha diferentes de acordo com cada membro, permitindo com que cada perfil tenha informações ou tarefas diferentes e específicas de acordo com o usuário;
- O login da triagem será de acesso único para os secretários(as) que exercem esta função, sendo assim possuindo um usuário e senha padrão para qualquer um que o utilizar. O papel do secretário(a) é exercer a triagem dos processos que contém os projetos submetidos e atrelá-los ao parecerista disponível no momento para que seja analisado e também comunicar com o responsável pelo processo a sua aprovação ou reprovação.
- Além das partes mais importantes do sistema como as citadas acima o usuário poderá obter informações extras relevantes através das múltuas funcionalidades do sistema, tais como consultar as leis e normas por trás da Comissão de Ética no Uso dos Animais, acessar o site da UNIVIÇOSA e outras formas de contato, acompanhar o status do processo dentre outras funcionalidades.

## Wireframe completo


# Prototipação
## Protótipo de alta fidelidade
Utilizamos o Figma como ferramenta para prototipar o sistema em alto nível para tornar a idealização feita através do Wireframe mais intuitiva e funcional, corrigindo alguns pontos e adaptando-os para fornecer a melhor experiência de uso ao usuário.
(colocar as telas principais do prototipo e depois o link de chamada para o prototipo completo)
- [Protótipo de alta fidelidade](https://www.figma.com/proto/SLbBgLLqG2Fb3pBHVnOHDK/SICEUA?type=design&node-id=1-3&t=CKfQnt72KW9yEfOt-0&scaling=scale-down-width&page-id=0%3A1&starting-point-node-id=1%3A3)
- (Para que a experiência com o protótipo seja a melhor possível, ao entrar neste link no canto superior direito haverá um ícone para maximizar a tela, clique neste ícone para que o protótipo fique melhor utilizável).

## Avaliação do protótipo
### Planejamento da avaliação
Para realizarmos a avaliação do protótipo nossa equipe se reunião e, com algumas opções de avaliação, optamos pela forma mais prática de mostrar o protótipo e suas funcionalidades juntamente com os requisitos que usamos para construí-lo, sendo ela uma reunião online "meet" no modelo worshop com a cliente para o qual estamos desenvolvendo o projeto do sistema. Agendamos esta reunião com a cliente para que pudessemos apresentar o protótipo e retirar mais informações e possíveis requisitos que antes não foram ditos ou notados.

### Execução da avaliação
Na data agendada, um dos representantes da nossa equipe iniciou a reunião e conversou com a cliente através de uma chamada de vídeo e a apresentou o nosso protótipo, dando ênfase em todas as funções presentes no protótipo que futuramente se tornariam o sistema em si.
Foram discutidas partes importantes da simulação do sistema como as funções e interfaces das telas de login, telas de triagem e de aprovação de projetos e principalmente, a tela de submissão de um projeto.
Foram revisados também os requisitos de alto nível do sistema para que a cliente os ouvisse e nos desse o feedback sobre o que estaria correto e o que poderíamos remodelar para encaixar dentro do que foi requisitado.

### Resultado da avaliação
Após a realização da reunião, nossa equipe analisou a conversa da cliente com nosso representante, através de um depoimento que o representante nos deu, e concluímos que o protótipo estava em sua maior parte de acordo com que propunham os requisitos do sistema, porém alguns detalhes teriam que ser alterados para atender de forma completa os requisitos da cliente. 
Estas mudanças e implementações foram:
- Incluir no protótipo uma funcionalidade que permita com que o parecerista que for analisar o projeto, caso o reprove, escreva o que deve ser alterado para que o projeto seja reenviado e aceito.
- A partir da definição do status do projeto, implementar uma função que envie um email para o responsável do projeto o deixando ciente de como está o andamento projeto.
- Implementar uma funcionalidade que gera um código que permite acompanhar o status do projeto pelo próprio sistema em tempo real.
- Simplificar a interface de login, integrando o que antes eram 2 sessões em somente uma, fazendo o reconhecimento do usuário de acordo com que for cadastrado pelo administrador do sistema.
- retirar a interface de submissão de projetos do cabeçalho da página e implementá-lo dentro da tela de login, integrando-o com os dois outros níveis de acesso e fazendo todo o controle de acesso através do usuário administrador.
Nosso grupo extraiu estas informações extras a partir da reunião e as definiu como requisitos do sistema, integrando-as nos documentos de requisitos e refinando estes requisitos para o nível de sistema.

## Processo contínuo
Os próximos passos para a conclusão do projeto seriam:
- Gravar e disponibilizar ao cliente um vídeo apresentando o protótipo de ponta a ponta, com todas funcionalidades e opções de navegação pelo sistema;
- [Vídeo explicativo do protótipo](https://drive.google.com/drive/folders/1hhH6SudeIuqPmBOMaTk80z0U9K4JsfhH)(Este é um vídeo explicativo, demonstrando a navegação por todo o protótipo deixando claro como cada funcionalidade foi abordada).
- Realizar o Pitch do projeto ao cliente ao cliente, aos especialistas e investidores, frizando novamente todas as funcionalidades do protótipo e mostrar como este sistema, se fosse realmente desenvolvido, ajudaria os stakeholders (pessoas afetadas pelo uso de um software) a resolver os problemas tangentes a falta de informatização no processo de avaliação de projetos do CEUA-UNIVIÇOSA;

# Conclusão
Com este projeto encerramos o Projeto Integrador, organizado pela professora e orientadora Cristiane Aparecida Lana.
Iniciado como uma proposta de projeto a atender demandas do NUPEX (Núcleo de Pesquisa e Extensão) da UNIVIÇOSA, o Projeto Integrador instigou o trabalho em equipe, organizado com a criação de empresas fictícias, tal como o entendimento de como funcionam todos os processos reais de um projeto de desenvolvimento de sotware dando ênfase a etapa da prototipação, desde a documentação até a prototipação de um sistema.
Durante todo o projeto foi nos proporcionado a integração entre cargos na empresa, tendo como papeis principais: CEO, Scrum Master, Analista de Sistemas, Poductor Owner e Designer.
Desta forma compreendemos como um colaborador pode ajudar o outro e o que cada um deve fazer como tarefas principais de seu cargo momentâneo.
#
### Este projeto foi desenvolvido pelos alunos:
- Arthur Duarte Mendes, Estudante de Desenvolvimento de Software da UNIVIÇOSA, [Github](https://github.com/Arthur0020)
- Vinicius Quintas Ferreira, Estudante de Desenvolvimento de Software da UNIVIÇOSA, [Github](https://github.com/ViniciusQuintas)
- Welley Henrique Dias, Estudante de Desenvolvimento de Software da UNIVIÇOSA, [Github](https://github.com/Weslley555)
- Luiz Eduardo Silva Araújo, Estudante de Desenvolvimento de Software da UNIVIÇOSA
- Fabrício Albuquerque, Estudante de Desenvolvimento de Software da UNIVIÇOSA
- Gabriella, Estudante de Desenvolvimento de Software da UNIVIÇOSA
- Augusto, Estudante de Desenvolvimento de Software da UNIVIÇOSA




