# Informatização do CEUA (Comitê de Ética no Uso de Animais).
<p align="center">
  <img src="https://github.com/Arthur0020/Projeto_integrador_NUPEX/assets/131721376/52baf8e3-896e-45cc-be2c-d746ad65a993" alt="Texto Alternativo">
</p>
<p align="center">Figura 1 - Logo do SICEUA</p>

# Visão geral
## O Desafio
O desafio central é evoluir o projeto do sistema, que está atualmente em uma fase pré-pronta, para um estágio de desenvolvimento completo e funcional. Para isso, é necessário:

- Refinar os Requisitos: Realizar uma análise minunciosa das necessidades e especificações atuais, garantindo que todas as funcionalidades essenciais sejam incorporadas no novo sistema. Isso envolve a tradução de requisitos de alto nível para especificações técnicas detalhadas, que orientarão o desenvolvimento do software.

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
  <img src="https://github.com/Arthur0020/Projeto_integrador_NUPEX/assets/131721376/91a435e0-b10f-47d5-a1a7-8c9628747669" alt="Modelo Estrela">
  </p>
<p align="center">Figura 2 - Ciclo de Vida Estrela</p>

# Análise de tarefas, usuários e função
## Why?
### Quem utilizará o sistema?
Neste primeiro momento de reflexão, não foi possível identificar as pessoas que fariam uso direto do sistema. No entanto, durante uma reunião com a coordenadora do CEUA, foi apresentada a seguinte divisão dos possíveis usuários: Professores, Pós-graduandos, Secretária, Pareceristas e Coordenadores.

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

- [Link para acessar o documento de Análise hierárquica de tarefas do SICEUA](https://drive.google.com/file/d/1JBc5Z9RgzqC3PWwV6W1wHQqsuNdiJ44T/view)
- Conforme introduzido o conceito de um documento de Análise hierárquica de tarefas, este é um diagrama com a hierarquia de tarefas que o SICEUA possui e que os usuários conseguem utilizar.

  
## Storytelling
"Ao revisar mais um lote de projetos submetidos ao CEUA, a Professora Clara percebeu que grande parte deles apresentava falhas e informações inconsistentes. Cada erro demandava tempo adicional, tornando suas noites mais longas e seus dias mais desgastantes. Clara, que sempre valorizou a ética e a precisão, sentia-se frustrada com o sistema manual atual. Ela sonhava com uma plataforma que pudesse validar automaticamente as submissões, destacando quaisquer inconsistências antes mesmo de chegarem a ela. Em uma manhã, durante uma reunião do comitê, foi apresentada a uma nova solução digital que prometia revolucionar seu processo de trabalho. Com essa nova ferramenta, Clara viu suas expectativas superadas: projetos completos e corretos, uma triagem mais rápida e uma comunicação eficiente com seus colegas. Agora, ela pode focar no que realmente importa: garantir que os projetos de pesquisa sejam eticamente sólidos e de alta qualidade."

"Passando pela mesma situação, Geovana, secretária do CEUA, chegava ao trabalho todos os dias com uma pilha de documentos esperando por sua triagem. O processo manual não só era exaustivo como também estava sujeito a erros humanos, o que frequentemente resultava em atrasos na avaliação dos projetos. Ela passava horas ao telefone e enviando e-mails para coordenar as atividades entre os pareceristas e os pesquisadores, tornando seu dia de trabalho estressante e pouco eficiente. Certo dia, em meio a um turbilhão de tarefas, foi convidada para testar um novo sistema digital. Ao começar a usar a nova plataforma, Geovana viu seu trabalho ser transformado. O sistema automatizava a triagem dos projetos, integrava ferramentas de comunicação e oferecia uma interface intuitiva. Agora, com apenas alguns cliques, Geovana gerencia todo o fluxo de projetos de maneira eficiente e sem os antigos obstáculos. Ela finalmente pôde dedicar seu tempo a tarefas mais estratégicas, sabendo que a coordenação e a comunicação no comitê estavam fluindo perfeitamente."



# WHO - Analise dos Stakeholders

## Personas
Com base nas hipóteses, storytelling e pesquisa com usuários, as personas foram criadas para representar os usuários que irão utilizar o produto:

<p align="center">
  <img src="https://github.com/Arthur0020/Projeto_integrador_NUPEX/assets/131721376/59603a61-a9d8-497f-b2df-4769ca9d8d91">
</p>  
<p align="center">Figura 3 - Persona da professora Clara</p>

<p align="center">
  <img src="https://github.com/Arthur0020/Projeto_integrador_NUPEX/assets/131721376/d97ab978-4fb3-4e74-940a-d76ad7ae2ad9">
</p>
<p align="center">Figura 4- Persona da secretária Geovana</p>


## Mapa de empatia
Com o intuito de entender as necessidades e as dores dos usuários, se colocando no lugar dele, foi desenvolvido um mapa de empatia considerando as personas que foram criadas.

### Mapas de empatia
<p align="center">
  <img src="https://github.com/Arthur0020/Projeto_integrador_NUPEX/assets/131721376/d5c39238-aad2-41c0-a84d-ad53221450f7">
</p>  
<p align="center">Figura 5 - Mapa de Empatia da professora Clara</p>

<p align="center">
  <img src="https://github.com/Arthur0020/Projeto_integrador_NUPEX/assets/131721376/48c7f45a-1e8a-4657-97da-d8bdf6be4927" alt="Mapa de empatia Geovana">
</p> 
<p align="center">Figura 6 - Mapa de Empatia da secretária Geovana</p>

## Avaliação - Analise de tarefa, usuários e função
### Análise de Tarefas
Para identificar as tarefas que os usuários do sistema precisariam realizar, foram analisadas todas as reuniões realizadas anteriormente, bem como os requisitos de usuário fornecidos à equipe. A validação dessas tarefas foi conduzida com os stakeholders por meio de uma reunião online, onde foi examinado como cada tarefa necessária para alcançar os resultados desejados no sistema impactaria positivamente o processo completo do usuário.

A utilização do documento de Análise Hierárquica de Tarefas (HTA) foi fundamental para identificar todas as ações possíveis a serem realizadas no sistema. Este documento proporcionou uma visão panorâmica do uso do sistema e permitiu a identificação de oportunidades para futuras implementações de novas funcionalidades. Com essa análise detalhada, a equipe pôde garantir que todas as tarefas essenciais estavam mapeadas e alinhadas com os objetivos dos usuários.

### Usuários
Após uma análise aprofundada dos stakeholders primários, os documentos de persona, mapa de empatia e storytelling foram remodelados para refletir melhor as características e o ambiente de trabalho dos usuários. A atualização desses documentos incluiu a aplicação de atributos que representam de forma mais precisa o dia a dia dos usuários e suas interações no contexto do sistema.

Esses novos documentos foram apresentados aos usuários para validação. O feedback recebido foi positivo, indicando que os documentos remodelados são agora mais fidedignos e representam com maior precisão o cenário diário dos stakeholders. Essa validação foi crucial para assegurar que a equipe de desenvolvimento compreendia plenamente as necessidades e expectativas dos usuários, permitindo um design mais centrado no usuário.

### Função
A análise de funções focou na identificação e definição clara das funções que cada tipo de usuário desempenharia dentro do sistema. Foram considerados os seguintes aspectos:

- Papéis e Responsabilidades: Definição dos diferentes papéis que os usuários assumiriam, tais como administrador, usuário final, gerente, entre outros. Cada papel foi detalhado com suas respectivas responsabilidades e permissões no sistema.
- Fluxo de Trabalho: Mapeamento do fluxo de trabalho para cada função, assegurando que os processos fossem otimizados e eficientes. Foram identificados pontos de integração entre diferentes funções para garantir uma operação coesa do sistema.

A validação dessas funções foi realizada com os stakeholders por meio de workshops e sessões de feedback, onde foi verificado se cada função estava bem definida e se atendia às necessidades operacionais dos usuários. O feedback obtido foi positivo, indicando que a definição das funções estava adequada e que o sistema estava preparado para suportar os diferentes papéis de maneira eficiente.

### Conclusão
A avaliação abrangente das tarefas, usuários e funções do sistema proporcionou uma compreensão detalhada das necessidades dos usuários e permitiu um alinhamento preciso entre as expectativas dos stakeholders e as funcionalidades do sistema. As validações realizadas garantiram que o sistema está sendo desenvolvido de acordo com os requisitos especificados e que está preparado para atender às demandas operacionais dos usuários de forma eficaz e segura.



# Engenharia de requisitos

## Elicitação de requisitos
A Elicitação de requisitos foi realizada através de uma reunião com a cliente que discorreu sobre os problemas que causavam o entrave no atual sistema de  submissão de projetos do CEUA, estes requisitos foram documentados a nível de usuário, ou seja, à um nível de explicação mais simples que a própria cliente consegue compreender.
- [Documento de requisitos a nível de Usuário](https://trello.com/c/WpOicLXP/34-requisitos-detalhados)


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
De acordo com as adequações da qual a cliente sugeriu para o protótipo, foi desenvolvido um wireframe de algumas telas com as mudanças que fariam diferença para a usabilidade dos stakeholders.
- Tela de Login unificada para todos os usuários.
- Tela do usuário parecerista e responsável pelo projeto com opções mais simples e funcionais para reencaminhar a outras informações.
- tela para se cadastrar como usuário responsável por um projeto para submete-lo.


## Wireframe completo
<p align="center">
  <img src="https://github.com/Arthur0020/Projeto_integrador_NUPEX/assets/131721376/5793cc5b-74af-4411-a648-250725ed8051">
</p> 
<p align="center">Figura 8 - Wireframe tela de login</p>

<p align="center">
  <img src="https://github.com/Arthur0020/Projeto_integrador_NUPEX/assets/131721376/eec3bed7-5c5c-4c71-b384-63a4f5f076a0">
</p> 
<p align="center">Figura 9 - Wireframe tela do parecerista</p>

<p align="center">
  <img src="https://github.com/Arthur0020/Projeto_integrador_NUPEX/assets/131721376/a6ee0f78-1f49-4124-9f00-39c8d34ffc2e">
</p> 
<p align="center">Figura 10 - Wireframe tela do responsável pela submissão do projeto</p>

<p align="center">
  <img src="https://github.com/Arthur0020/Projeto_integrador_NUPEX/assets/131721376/af4b9ba0-3e4e-4969-b00e-5f3fb4645838">
</p> 
<p align="center">Figura 11 - Wireframe cadastro de usuário</p>

## Avaliação - Projeto conceitual e especificações do design
### Metodologia de Validação
A validação do projeto conceitual do sistema foi conduzida com a cliente por meio de uma reunião online. Durante esta sessão, foram apresentados os detalhes das implementações realizadas, evidenciando como as abstrações do conceito do projeto foram materializadas. Este processo incluiu uma revisão minuciosa de cada especificação implementada, verificando sua conformidade com os requisitos e preferências previamente definidos pelo cliente.

### Verificação das Especificações
Para assegurar que cada aspecto do projeto atendia às expectativas do cliente, foi adotada uma abordagem sistemática de verificação das especificações. Isso envolveu a análise detalhada dos seguintes pontos:
- Requisitos Funcionais: Verificação das funcionalidades implementadas para garantir que todas as necessidades operacionais do cliente foram contempladas.
- Requisitos Não Funcionais: Avaliação de aspectos como performance, segurança e usabilidade para confirmar que o sistema não apenas atende aos requisitos funcionais, mas também oferece uma experiência de usuário satisfatória.
- Preferências Estéticas e de Design: Comparação entre o design implementado e as preferências estéticas do cliente, incluindo layout, esquema de cores e interface do usuário.

### Feedback da Cliente
O feedback recebido da cliente foi amplamente positivo. Ela destacou que o conceito geral do sistema, bem como o design aplicado, estavam alinhados com suas expectativas. Este retorno positivo foi crucial para validar o trabalho da equipe de desenvolvimento, proporcionando um direcionamento claro e confirmando que o projeto está no caminho certo para atender às necessidades do cliente.

### Conclusão
A avaliação do projeto conceitual e das especificações do design não apenas validou as implementações realizadas até o momento, mas também reforçou a confiança da equipe no desenvolvimento contínuo do sistema. A clareza e o alinhamento com as expectativas do cliente são essenciais para o sucesso do projeto, e o feedback positivo obtido indica que estamos progredindo de forma satisfatória.

# Prototipação
## Protótipo de alta fidelidade
Foi utilizado o Figma como ferramenta para prototipar o sistema em alto nível, visando tornar a idealização feita através do wireframe mais intuitiva e funcional. Durante este processo, foram corrigidos alguns pontos e adaptados para proporcionar a melhor experiência de uso ao usuário.
- O protótipo completo está no link disponibilizado abaixo e as telas principais de cada usuário do sistema estão nas figuras 12, 13, 14 e 15. Há abaixo também um link para um vídeo utilizando o protótipo e mostrando suas principais funções.
- [Protótipo de alta fidelidade](https://www.figma.com/proto/3jGAXG6ZiGCrDdOMjSLHJz/SICEUA---NOVO?node-id=1-3&t=h64gtMbGVLLiwKEl-0&scaling=contain&page-id=0%3A1&starting-point-node-id=1%3A3&show-proto-sidebar=1)
- [Vídeo explicativo sobre o protótipo e suas funcionalidades](link)

<p align="center">
  <img src="https://github.com/Arthur0020/Projeto_integrador_NUPEX/assets/131721376/f77bde8e-d8bd-4f30-b7b4-09dcf6071e7c alt="Login principal">
</p>
<p align="center">Figura 12 - Interface Principal de Login</p>

<p align="center">
  <img src="https://github.com/Arthur0020/Projeto_integrador_NUPEX/assets/131721376/74e97e4e-c3ea-4e18-b52f-9a23c5e7c40e alt="Interface principal do parecerista">
</p>
<p align="center">Figura 13 - Interface principal do parecerista</p>

<p align="center">
  <img src="https://github.com/Arthur0020/Projeto_integrador_NUPEX/assets/131721376/4d8b69de-e337-419d-924c-252b99d0b4ba alt="Interface principal da triagem">
</p>
<p align="center">Figura 14 - Interface principal da triagem</p>

<p align="center">
  <img src="https://github.com/Arthur0020/Projeto_integrador_NUPEX/assets/131721376/1c21758e-4339-41a4-b05c-d5c2901b3618 alt="Interface principal do responsável por submeter um projeto">
</p>
<p align="center">Figura 15 - Interface principal do responsável por submeter um projeto"</p>


## Avaliação do protótipo
## Avaliação parcial de requisitos e funcionalidades básicas do protótipo
### Metodologia da avaliação
Para realizar a avaliação do protótipo, a equipe se reuniu e, entre várias opções de avaliação, optou pela forma mais prática de apresentar o protótipo e suas funcionalidades juntamente com os requisitos utilizados para construí-lo. Foi organizada uma reunião online tipo workshop com a cliente para quem o projeto do sistema está sendo desenvolvido. Agendamos esta reunião com a cliente para que pudessemos apresentar o protótipo e retirar mais informações e possíveis requisitos que antes não foram ditos ou notados.

### Execução da avaliação
Na data agendada, um dos representantes da equipe iniciou a reunião e conversou com a cliente através de uma chamada de vídeo, apresentando o protótipo e destacando todas as funções presentes que seriam implementadas no sistema final. Durante a reunião, foram discutidos aspectos importantes da simulação do sistema, como as funções e interfaces das telas de login, triagem, aprovação de projetos e, especialmente, a tela de submissão de projetos. Também foram revisados os requisitos de alto nível do sistema para que a cliente desse feedback sobre o que estava correto e sugerisse ajustes conforme necessário.

### Resultado da avaliação
Após a realização da reunião, a equipe analisou a conversa da cliente com o representante por meio de um depoimento fornecido por ele. Foi concluído que o protótipo estava em sua maior parte alinhado com os requisitos do sistema propostos, porém algumas alterações seriam necessárias para atender completamente às necessidades da cliente. As mudanças e implementações acordadas foram:
- Incluir no protótipo uma funcionalidade que permita com que o parecerista que for analisar o projeto, caso o reprove, escreva o que deve ser alterado para que o projeto seja reenviado e aceito.
- A partir da definição do status do projeto, implementar uma função que envie um email para o responsável do projeto o deixando ciente de como está o andamento projeto.
- Implementar uma funcionalidade que gera um código que permite acompanhar o status do projeto pelo próprio sistema em tempo real.
- Simplificar a interface de login, integrando o que antes eram 2 sessões em somente uma, fazendo o reconhecimento do usuário de acordo com que for cadastrado pelo administrador do sistema.
- retirar a interface de submissão de projetos do cabeçalho da página e implementá-lo dentro da tela de login, integrando-o com os dois outros níveis de acesso e fazendo todo o controle de acesso através do usuário administrador.
A equipe extraiu estas informações extras a partir da reunião e as definiu como requisitos do sistema, integrando-as nos documentos de requisitos e refinando estes requisitos para o nível de sistema.

## Avaliação final de usabilidade pelo usuário
### Metodologia de Avaliação da parecerista 
Na avaliação final de usabilidade, foi realizada uma reunião online com a cliente. Durante essa sessão, a cliente foi instruída a alcançar metas específicas dentro do sistema, tais como avaliar projetos submetidos, submeter novos projetos e conferir funcionalidades básicas do protótipo. O objetivo era testar a navegabilidade intuitiva do sistema e a eficácia dos elementos de affordance implementados.

### Execução da Avaliação com a parecerista
A cliente navegou pelo protótipo utilizando sua intuição, com base nos elementos de affordance e design orientado ao usuário. Um membro da equipe estava presente para observar e explicar o comportamento do protótipo, destacando cada funcionalidade importante e como ela deveria ser utilizada. Esse acompanhamento garantiu que a cliente compreendesse plenamente cada aspecto do protótipo e pudesse fornecer feedback detalhado.

### Resultado da avaliação com a parecerista
Durante a avaliação, a cliente destacou vários pontos para revisão e melhoria:

- Opção de Pendência na Avaliação de Projetos:
A cliente sugeriu que, dentro da interface de avaliação de projetos, fosse incluída a opção de deixar um projeto em pendência para exigir alguma alteração específica, além das opções de aprovar ou reprovar. Esta funcionalidade permitiria um controle mais refinado e flexível sobre o processo de avaliação de projetos.

- Documentação Específica por Tipo de Projeto:
A cliente mencionou que cada tipo de experimento possui termos e documentações específicas exigidas. Ela sugeriu que o sistema fosse capaz de identificar o tipo de projeto submetido e, automaticamente, selecionar e solicitar apenas os documentos complementares necessários para aquele tipo de projeto. Essa funcionalidade melhoraria significativamente a eficiência e a precisão no processo de submissão de projetos.

### Metodologia de Avaliação da Triagem
Na avaliação final de usabilidade, foi realizada uma reunião presencial com a cliente. Durante essa sessão, o protótipo foi apresentado diretamente à cliente, validando as funcionalidades implementadas. O objetivo era testar a navegabilidade intuitiva do protótipo e a eficácia dos elementos de affordance implementados.

### Execução da Avaliação com a Triagem
Durante a avaliação, o representante da equipe mostrou as funcionalidades do protótipo para a cliente, conforme sua preferência. A cliente observou o protótipo enquanto o representante navegava por ele, explicando o comportamento de cada funcionalidade e destacando os elementos importantes. Esse formato garantiu que a cliente compreendesse plenamente cada aspecto do protótipo e pudesse fornecer feedback detalhado.

### Resultado da Avaliação com a Triagem
Durante a avaliação, a cliente destacou a necessidade de revisão em um ponto específico:

Opção de Pendência na Avaliação de Projetos:
- A cliente sugeriu que, dentro da interface de avaliação de projetos e de relação de projetos, fosse incluída a opção de deixar um projeto em pendência para exigir alguma alteração específica, além das opções de aprovar ou reprovar. Esta funcionalidade permitiria um controle mais refinado e flexível sobre o processo de avaliação de projetos.

### Conclusão
Após o término de cada reunião, foi utilizado o questionário SUS, que ajuda a quantificar a usabilidade de um sistema de acordo com a resposta dos usuários às perguntas feitas.
A pontuação média final do questionário foi de 80,2 o que garante uma usabilidade do sistema considerávelmente acima da média.
- [Clique aqui para acessar o modelo do questionário utilizado e a pontuação adquirida](https://drive.google.com/drive/folders/1Q8MI-h2RDcS_qzb9IcafoqA51uLsLLnl?usp=sharing)
#
Esta avaliação final de usabilidade foi crucial para identificar áreas de melhoria no protótipo do sistema. O feedback fornecido pelas clientes não apenas validou muitas das funcionalidades implementadas, mas também destacou oportunidades importantes para refinamento e aprimoramento.

## Trabalhos futuros
### Os próximos passos do projeto incluirão
- Adequar o projeto a todos os feedbacks relatados pelos stakeholders
- Implementação das Sugestões: Adicionar a opção de pendência na interface de avaliação de projetos e desenvolver a funcionalidade de seleção automática de documentos complementares baseados no tipo de projeto.
- Testes Adicionais: Realizar testes adicionais com a cliente e outros usuários para validar as novas funcionalidades e garantir que as melhorias atendam às necessidades operacionais.
- Refinamento Contínuo: Continuar a iterar sobre o design e a funcionalidade do sistema com base no feedback contínuo dos usuários, garantindo que o sistema evolua de maneira a proporcionar a melhor experiência de usuário possível.
  
Essa abordagem de avaliação e refinamento contínuos assegura que o sistema não apenas atenda, mas exceda as expectativas dos usuários, oferecendo uma solução robusta e intuitiva para suas necessidades.

# Conclusão
Com esta continuação do primeiro projeto, encerramos o Projeto Integrador organizado pela professora e orientadora Cristiane Aparecida Lana. Iniciado como uma proposta de projeto para atender demandas do NUPEX (Núcleo de Pesquisa e Extensão) da UNIVIÇOSA, o Projeto Integrador promoveu o trabalho em equipe, simulando a criação de empresas fictícias e proporcionando o entendimento de todos os processos reais de um projeto de desenvolvimento de software, com ênfase na etapa de prototipação, desde a documentação até a criação de um sistema funcional. Ao longo do projeto, houve integração entre os diferentes cargos na empresa fictícia, como CEO, Scrum Master, Analista de Sistemas, Product Owner e Designer. Isso permitiu compreender como cada colaborador pode contribuir e quais são as responsabilidades principais de cada função durante o projeto.
#
### A primeira versão deste projeto foi desenvolvida pelos alunos:
- Arthur Duarte Mendes, Estudante de Desenvolvimento de Software da UNIVIÇOSA, [Github](https://github.com/Arthur0020)
- Vinicius Quintas Ferreira, Estudante de Desenvolvimento de Software da UNIVIÇOSA, [Github](https://github.com/ViniciusQuintas)
- Welley Henrique Dias, Estudante de Desenvolvimento de Software da UNIVIÇOSA, [Github](https://github.com/Weslley555)
- Luiz Eduardo Silva Araújo, Estudante de Desenvolvimento de Software da UNIVIÇOSA
### O aprimoramento deste projeto foi desenvolvido pelos alunos:
- Arthur Duarte Mendes, Estudante de Desenvolvimento de Software da UNIVIÇOSA
- Vinicius Quintas Ferreira, Estudante de Desenvolvimento de Software da UNIVIÇOSA
- Gabriella Moreira Ribeiro, Estudante de Desenvolvimento de Software da UNIVIÇOSA
- Fabrício Albuquerque, Estudante de Desenvolvimento de Software da UNIVIÇOSA
- Augusto Antunes, Estudante de Desenvolvimento de Software da UNIVIÇOSA
- Thiago Rafael, Estudante de Desenvolvimento de Software da UNIVIÇOSA




