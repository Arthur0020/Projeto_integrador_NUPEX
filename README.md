# Estudo de caso: Informatizar o setor do CEUA (Comitê de Ética no Uso de Animais).
<p align="center">
  <img src="https://github.com/Arthur0020/Projeto_integrador_NUPEX/assets/131721376/52baf8e3-896e-45cc-be2c-d746ad65a993" alt="Texto Alternativo">
</p>
imagem 1

# Visão geral
## O Desafio
Refinar requisitos de alto nível para nível técnico para auxiliar no desenvolvimento de sistema de software que tem como finalidade promover a avaliação e aprovação de projetos pelo Comitê de Ética no Uso de Animais do Centro Universitário de Viçosa - UNIVIÇOSA.

## Contexto
Atualmente o CEUA não possui um sistema digital para realizar suas atividades de avaliações de projetos envolvendo o uso de animais, sendo todos feitos manualmente, o que acaba por tornar todo o processo bem trabalhoso e passível de possíveis falhas, além de acabar perdendo tempo com pequenos detalhes e deta forma tornando-se não muito efetivo para os usuários. 
Existem diversas melhorias que podem ser realizadas no atual método usado pelo CEUA para que ele se torne apropriado para seus usuários finais, de tal forma com que aumente a produtividade e efetividade.

# Ciclo de vida
## Ciclo de vida Estrela
O modelo estrela representa o ciclo de vida do desenvolvimento de software, focando em uma abordagem iterativa e centrada no usuário, dando ênfase na flexibilidade e na capacidade de adaptação às necessidades e feedback dos usuários durante todo o processo de desenvolvimento. O modelo de ciclo de vida estrela é especialmente útil em projetos onde os requisitos podem mudar com frequência ou onde a validação contínua com o usuário é crucial para o sucesso do sistema. Ele promove um desenvolvimento ágil e adaptativo, alinhando as práticas modernas de engenharia de software e desenvolvimento centrado no usuário.

<p align="center">
  <img src="![Modelo-de-ciclo-de-vida-Estrela](https://github.com/Arthur0020/Projeto_integrador_NUPEX/assets/163935730/c12987ce-5714-4ff3-89fd-2475e1805ace)" alt="Modelo Estrela">
  </p>
imagem 2

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
(colocar aqui a análise de tarefas) - fabricio está fazendo

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
  <img src="https://github.com/Arthur0020/Projeto_integrador_NUPEX/assets/131721376/bd56f1a8-6e96-42c9-a559-0bf2ab1c71f5" alt="Persona Clara Souza">
</p>
imagem 3

<p align="center">
  <img src="https://github.com/Arthur0020/Projeto_integrador_NUPEX/assets/131721376/b272d6c3-112c-4be9-bace-66071aa0e15e" alt="Persona Miguel Almeida">
</p>  
imagem 4

## Mapa de empatia
Com o intuito de entender as necessidades e as dores dos usuários, se colocando no lugar dele, foi desenvolvido um mapa de empatia considerando as personas que foram criadas.

### Mapas de empatia
<p align="center">
  <img src="https://github.com/Arthur0020/Projeto_integrador_NUPEX/assets/131721376/0febe0b1-bd56-49d1-bfd5-afd17682c97f" alt="Mapa de empatia Miguel">
</p>  
imagem 5

<p align="center">
  <img src="https://github.com/Arthur0020/Projeto_integrador_NUPEX/assets/131721376/78ba9dee-1c81-4d20-a058-96a8a12393d1" alt="Mapa de empatia Clara">
</p> 
imagem 6

## Avaliação - analise de tarefa usuários e função
(Fazer aqui a avaliação)

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
imagem 7

## Wireframe
Levando em consideração os requisitos funcionais e as referências que foram nos passadas pela coordenadora do CEUA, nós desenvolvemos um protótipo utilizando Wireframe da qual contém todas as funcionalidades cruciais idealizadas para que possam ser posteriormente prototipadas em alto nível.
- Na interface inicial do site é possível se acessar 4 funcionalidades principais com 2 subfuncionalidades cada uma que levam o usuário a diferentes interfaces de acordo com a escolha de determinada funcionalidade;
- Na interface inicial também se encontram as funcionalidades de login, da qual são divididas em 2 opções sendo a primeira o login para os pareceristas(analistas de projetos) e a segunda para a triagem de processos;
- O login dos pareceristas contará com usuário e senha diferentes de acordo com cada membro, permitindo com que cada perfil tenha informações ou tarefas diferentes e específicas de acordo com o usuário;
- O login da triagem será de acesso único para os secretários(as) que exercem esta função, sendo assim possuindo um usuário e senha padrão para qualquer um que o utilizar. O papel do secretário(a) é exercer a triagem dos processos que contém os projetos submetidos e atrelá-los ao parecerista disponível no momento para que seja analisado e também comunicar com o responsável pelo processo a sua aprovação ou reprovação.
- Além das partes mais importantes do sistema como as citadas acima o usuário poderá obter informações extras relevantes através das múltuas funcionalidades do sistema, tais como consultar as leis e normas por trás da Comissão de Ética no Uso dos Animais, acessar o site da UNIVIÇOSA e outras formas de contato, acompanhar o status do processo dentre outras funcionalidades.

## Wireframe completo
<p align="center">
  <img src="https://github.com/Arthur0020/Projeto_integrador_NUPEX/assets/131721376/d5761da9-5556-4d92-8816-5e19a7ae7db3" alt="Interface inicial">
</p> 
imagem 8

<p align="center">
  <img src="https://github.com/Arthur0020/Projeto_integrador_NUPEX/assets/131721376/a5fd54f9-eab4-40a4-a902-9d30916c95a3" alt="Interface inicial e opções de escolha">
</p> 
imagem 9

<p align="center">
  <img src="https://github.com/Arthur0020/Projeto_integrador_NUPEX/assets/131721376/665fa65f-0f96-485e-8708-51295c9bcc73" alt="Regimento interno">
</p> 
imagem 10

<p align="center">
  <img src="https://github.com/Arthur0020/Projeto_integrador_NUPEX/assets/131721376/c1c88080-7260-4cb1-a8ca-e4889f7069ab" alt="Leis">
</p> 
imagem 11

<p align="center">
  <img src="https://github.com/Arthur0020/Projeto_integrador_NUPEX/assets/131721376/b022276c-7989-4092-9e4a-b15585e14058" alt="Normas">
</p> 
imagem 12

<p align="center">
  <img src="https://github.com/Arthur0020/Projeto_integrador_NUPEX/assets/131721376/0a876a7e-9014-45c7-803f-2e5fa68f7a53" alt="Submissão de projetos">
</p> 
imagem 13

<p align="center">
  <img src="https://github.com/Arthur0020/Projeto_integrador_NUPEX/assets/131721376/0ea7df0c-1c4b-4a49-a35e-e5622ff21b86" alt="Formulário de uso animal">
</p> 
imagem 14

<p align="center">
  <img src="https://github.com/Arthur0020/Projeto_integrador_NUPEX/assets/131721376/b0a4474b-bbe5-4314-8dc0-d66df8c1ee68" alt="Formulário de material biológico">
</p>
imagem 15

<p align="center">
  <img src="https://github.com/Arthur0020/Projeto_integrador_NUPEX/assets/131721376/5e5c8e8a-b117-48f6-bf20-4ae832bd0c83" alt="Consulta de processos">
</p>
imagem 16

<p align="center">
  <img src="https://github.com/Arthur0020/Projeto_integrador_NUPEX/assets/131721376/220928b4-ef23-4e31-aded-eb579dcd5985" alt="Acompanhamento do processo">
</p>
imagem 17

<p align="center">
  <img src="https://github.com/Arthur0020/Projeto_integrador_NUPEX/assets/131721376/61dc83f9-82fb-4969-a7d8-24c420964edf" alt="Área de trabalho da triagem">
</p>
imagem 18

<p align="center">
  <img src="https://github.com/Arthur0020/Projeto_integrador_NUPEX/assets/131721376/525344bf-84ed-42ab-abb1-8e0812c6c699" alt="Área de trabalho do parecerista">
</p>
imagem 19

# Prototipação
## Protótipo de alta fidelidade
Utilizamos o Figma como ferramenta para prototipar o sistema em alto nível para tornar a idealização feita através do Wireframe mais intuitiva e funcional, corrigindo alguns pontos e adaptando-os para fornecer a melhor experiência de uso ao usuário.
(colocar as telas principais do prototipo e depois o link de chamada para o prototipo completo)
- [Protótipo de alta fidelidade](https://www.figma.com/proto/SLbBgLLqG2Fb3pBHVnOHDK/SICEUA?type=design&node-id=1-3&t=CKfQnt72KW9yEfOt-0&scaling=scale-down-width&page-id=0%3A1&starting-point-node-id=1%3A3)
- (Para que a experiência com o protótipo seja a melhor possível, ao entrar neste link no canto superior direito haverá um ícone para maximizar a tela, clique neste ícone para que o protótipo fique melhor utilizável).

## Avaliação do protótipo
### Planejamento da avaliação

### Execução da avaliação

### Resultado da avaliação

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
Agradecimento especial ao aluno Guilherme Galante, que ingressou neste projeto junto com a equipe e ajudou muito, mas teve que sair na metade por motivos pessoais, [Github](https://github.com/GuilhermeGalante)



