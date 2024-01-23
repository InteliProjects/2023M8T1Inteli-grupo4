# Tecnologia Assistiva: Desenvolvimento de um Compilador e um Ambiente de Desenvolvimento Integrado com Tapete Sensorial para Estimulação de Pessoas com Leves Desordens Neurológicas

André Lessa, Gabriel Carneiro, Leandro Custódio, Sarah Ribeiro, Stefano Butori, Vinicius Santos e Yasmin Vitória

<hr>

**Resumo**

Este artigo aborda o desenvolvimento de um compilador e um Ambiente de Desenvolvimento Integrado (IDE) dedicados à Tecnologia Assistiva (TA), com foco em estimular pessoas que enfrentam leves desordens neurológicas, especialmente aquelas atendidas pela Associação de Assistência à Criança Deficiente (AACD). A AACD presta assistência a uma variedade de condições, como paralisia cerebral, amputações, poliomielite, doenças neuromusculares, etc. Caracterizadas por distúrbios no controle motor, postura e possíveis complicações sensoriais, cognitivas e de comunicação. O objetivo deste projeto é fornecer um ambiente inovador para terapia assistiva, utilizando um tapete sensorial conectado ao Greg Maker. Este recurso visa proporcionar um affordance adequado para respostas de pacientes com leves desordens neurológicas, melhorando desempenhos ocupacionais e facilitando a realização de Atividades de Vida Diária (AVDs).

**Palavras-chave** - Tecnologia Assistiva; Compiladores; IDE; Tapete Sensorial.

<hr>

**Abstract**

This article addresses the development of a compiler and an Integrated Development Environment (IDE) dedicated to Assistive Technology (AT), with a focus on stimulating individuals facing mild neurological disorders, particularly those served by the Associação de Assistência à Criança Deficiente (AACD). AACD provides assistance for a variety of conditions such as cerebral palsy, amputations, polio, neuromuscular diseases, etc. These conditions are characterized by motor control disorders, posture issues, and potential sensory, cognitive, and communication complications. The goal of this project is to provide an innovative environment for assistive therapy, utilizing a sensory mat connected to the Greg Maker. This feature aims to offer suitable affordances for responses from patients with mild neurological disorders, improving occupational performance and facilitating the execution of Activities of Daily Living (AVDs).

**Keywords** - Assistive Technology; Compilers; IDE; Sensory Mat.

## 1. Introdução 

A Terapia Ocupacional desempenha um papel crucial na reabilitação de pacientes com paralisia cerebral, conforme descrito em Zilli (2013). De acordo com este artigo,  esta terapia foca no desenvolvimento e melhoria da funcionalidade e independência do paciente em atividades diárias. Ela proporciona benefícios significativos, como a melhoria da coordenação motora, o aumento da independência, a promoção da inclusão social e a melhoria da qualidade de vida. Os terapeutas ocupacionais (TO) utilizam uma variedade de técnicas e estratégias para ajudar os pacientes a superar limitações físicas e cognitivas, dentre elas a tecnologia assistiva (TA).

O trabalho de Alves, Emmel e Matsukura (2012) e Calheiros, Mendes e Lourenço (2018) discutem a evolução da terapia ocupacional no Brasil, destacando o atraso na adoção de tecnologias assistivas em comparação com países da América do Norte e Europa. Esse atraso é atribuído a fatores como escassez de recursos financeiros, limitações no financiamento público e privado, e falta de conhecimento técnico entre profissionais de reabilitação. 

Tecnologia Assistiva, conforme descrito no trabalho de Bersch (2008), refere-se ao conjunto de recursos e serviços que ajudam a melhorar a funcionalidade e a independência de pessoas com deficiência ou mobilidade reduzida. Segundo o artigo, a importância dessa tecnologia reside na sua capacidade de promover a inclusão social, aumentar a autonomia e a qualidade de vida, facilitando o acesso a atividades cotidianas e contribuindo para uma maior participação na sociedade. A Tecnologia Assistiva engloba desde dispositivos simples até sistemas tecnológicos avançados, adaptados às necessidades individuais de cada pessoa.

O artigo apresenta uma colaboração inovadora entre a AACD e o Inteli, visando superar essas barreiras na implementação de tecnologia assistiva, por meio de um projeto que visa simplificar o trabalho do TO nas atividades com pacientes com leves desordens neurológicas. 

O projeto desenvolvido utiliza tapetes sensoriais conectados através do Greg Maker — um kit de criatividade que possibilitando a invenção de novos objetos a partir de materiais cotidianos — integrando-os a uma plataforma de desenvolvimento intuitiva que permite a criação e execução de jogos, criados pela TO. O uso de tapete sensorial, e a IDE, é especificamente projetado para estimular pessoas com leves desordens neurológicas, contribuindo para a adoção de soluções de TA efornecendo alternativas OpenSource para outras iniciativas. 

Este artigo tem como objetivo explorar o desenvolvimento e a implementação desse projeto terapêutico adaptativo, delineando seu escopo, objetivos, benefícios esperados e materiais de estudo associados. Ao fazer isso, busca-se destacar o papel transformador da tecnologia desenvolvida na promoção de soluções inclusivas e adaptativas para comunidades diversas.

## 2. Trabalhos relacionados 

Dentre os trabalhos correlatos, destaca-se a pesquisa conduzida por Nazari et al., (2017). O estudo aborda a temática da TA, que compreende dispositivos, técnicas e processos destinados a fornecer assistência ou reabilitação para pessoas com algum tipo de deficiência. O objetivo principal do artigo é apresentar o conceito de TA, suas categorias e discutir a legislação brasileira relacionada à Tecnologia Assistiva como uma política pública de educação inclusiva, com os resultados das análises conduzidas por esse estudo podemos estimar o impacto que o projeto que está sendo conduzido pode gerar.

Adicionalmente, no contexto da Tecnologia Assistiva, vale ressaltar o estudo de Petry, Mafalda e Zangerolami (2018). Esse trabalho fornece insights sobre a aplicação prática da tecnologia assistiva, especificamente um tapete sensorial, para crianças autistas na faixa etária de 0 a 4 anos, destacando a relevância dessas soluções inovadoras na promoção do desenvolvimento infantil.

Dentre os trabalhos citados no nosso projeto, a revisão sistemática dos procedimentos da Terapia Ocupacional na Paralisia Cerebral (ZILLI, F. 2013) tem o objetivo de elucidar os benefícios gerados pela Terapia Ocupacional na reabilitação de pacientes acometidos pela paralisia cerebral, bem como revisar conceitos da patologia; coletar dados e referências utilizadas como intervenção pelos terapeutas ocupacionais, explanando os possíveis benefícios gerados pela inclusão do mesmo na reabilitação desta clientela. Sendo assim, uma pesquisa relevante para o projeto, levando em conta esse artigo, é possível observar a importância do objeto de estudo do projeto.

O estudo de Noschang et al., (2014), fornece uma base teórica fundamental para o objeto de estudo deste projeto, especialmente ao considerar a dificuldade que uma pessoa leiga na área de tecnologia pode enfrentar ao tentar criar uma IDE didática e concisa.

Essas referências são exemplos concretos de trabalhos relacionados que fortalecem a base teórica do projeto proposto, proporcionando uma compreensão mais aprofundada sobre a interseção entre tecnologia assistiva, compiladores e a inovação apresentada neste artigo científico.

## 3. Materiais e métodos
O presente projeto foi desenvolvido a partir da metodologia ágil, sendo esta a metodologia Scrum, o qual quebra atividades em etapas para prazos específicos a cada duas semanas, totalizando dez semanas para o processo de construção do foco que engloba o compilador, aplicação Desktop e a implementação do tapete sensorial. Este tipo de metodologia auxiliou no processo de planejamento e organização, o qual garante maior eficiência e qualidade, além de trazer resultados com maior destreza.

Tal metodologia oportuniza uma estruturação de projeto que torna os objetivos mais tangíveis, dividindo em cinco sprints o qual cada uma possui um prazo de duas semanas de conclusão, contendo atividades estabelecidas na chamada Sprint Planning, que marca o início de cada sprint e o alinhamento do que será entregue num modelo de lista, enquanto a Sprint Retrospective é o fechamento, tendo o papel de promover a melhoria contínua, revendo pontos que merecem maior foco e o que pode ser mudado ou mantido. A equipe que participa destes eventos, possui característica multidisciplinar, tendo programadores e designers que atuam em conjunto com profissionais da área de terapia ocupacional a fim de entregar um produto que atenda as expectativas de ambos.

Desse modo, para atender as demandas de cada sprint, houve prioridades envolvendo o nível de importância de cada funcionalidade, ferramentas e tecnologias a serem implementadas. A respeito da linguagem de programação,o compilador foi implementado utilizando a linguagem de programação Python. A escolha desta linguagem foi motivada pela sua sintaxe clara e concisa, facilitando a criação de um compilador eficiente e de fácil manutenção, visto que apresenta versatilidade, contribuindo para desempenhar um papel crucial de instruções escritas em termos de programação para um formato executável, permitindo a interação entre hardware e software. 
Em relação a essa interação do físico e digital, o compilador foi projetado para se comunicar eficientemente com o Greg Maker, um kit de pequenas ferramentas e ligações que tem características criativas, sendo utilizado para conectar o tapete sensorial ao sistema. A integração permite que o compilador receba entradas do tapete sensorial, possibilitando a criação de respostas personalizadas para pacientes com leves desordens neurológicas e que estes tenham retornos a respeito dos estímulos gerados.

Para um formato executável, o processo de compilação transforma o código-fonte escrito pelos terapeutas ocupacionais em um formato executável compatível com o sistema operacional Microsoft Windows, usado como padrão. Essa abordagem visa garantir a acessibilidade e a facilidade de uso para os usuários finais. Adotando este sistema operacional como padrão para auxiliar no uso da IDE, em cima disso, torna a aplicação Desktop usável a partir de recursos e desenvolvimento de código que permitem o sistema ser real e funcional. Sendo assim, a aplicação desktop foi construída utilizando o framework Electron, que facilita o desenvolvimento de aplicações desktop multiplataforma. Esse framework permite a combinação de tecnologias e linguagens de programação para criar uma interface intuitiva e funcional. O React.js foi adotado para criar componentes visuais e funcionais da aplicação desktop, enquanto a programação em blocos foi implementada para simplificar o processo de criação de atividades jogáveis, permitindo que terapeutas ocupacionais desenvolvam jogos sem a necessidade de conhecimento avançado em programação, tendo a presença de duas linguagens, sendo estas JavaScript e Python.

Ademais, para fazer as devidas projeções, a forma de embasamento que transcende pesquisas, também marca forte presença de validações e métodos qualitativos como feedbacks oriundos de profissionais que participam de forma ativa no processo de construção da solução. Por meio de avaliações presenciais e práticas de usabilidade, foi presente observações e sugestões que acarretaram em mudanças constantes até o aperfeiçoamento. Este aspecto de usabilidade foi essencial para verificar pontos importantes que abordam a acessibilidade e inclusão, desde a facilidade de navegação na aplicação, até a compreensão da programação em blocos e a interação eficaz com o tapete sensorial, tanto para o entendimento dos profissionais que conduzem sessões, quanto para o conforto dos pacientes com paralisia cerebral. 

Os testes de usabilidade refletiram não apenas a eficiência técnica da aplicação, mas também a capacidade de proporcionar uma experiência de terapia assistiva significativa. Os testes diretos de usabilidade focaram nas principais funcionalidades, incluindo a criação de atividades personalizadas, a interação com o tapete sensorial e a mensuração do impacto no desempenho dos pacientes. Todavia, conforme a efetuação de testes, salienta-se a ciência dos objetivos do projeto e dos procedimentos envolvidos ao tratar-se principalmente da segurança e imagem. Dessa maneira, medidas para garantir a privacidade e segurança dos dados dos pacientes e qualquer informação sensível ou uso de imagem, deve ser rigorosamente protegida e tratada com confidencialidade. Tal aspecto de segurança, concebeu uma das motivações de adotar o modelo Desktop como ideal, visto que a característica de ser usado na máquina local garante maior segurança aos dados e além disso, como forma de reforço, métodos de autenticação referente a registro e login foram necessárias.

Esta seção demonstrou que o projeto parte dos princípios da inovação ao integrar tecnologia assistiva na área da saúde, de forma personalizada para estimular pacientes, como também facilitar o exercício da profissão de terapeuta ocupacional. Com uma equipe multidisciplinar, testes e validações frequentes com fontes confiáveis e profissionais da área alvo, possibilitou o progresso e uma solução funcional que atende às necessidades e que possui o intuito de apoiar o desenvolvimento contínuo de crianças com paralisia cerebral.


## 4. Resultados 

A partir da recapitulação introdutória e associação de análises e estudos, tratando-se de aspectos relacionados ao desenvolvimento de pacientes com paralisia cerebral(PC) por meio de instrumentos tecnológicos, atende-se ao propósito centralizado na elaboração de uma IDE que favoreça o trabalho e a interação entre profissional e paciente. Isso age na transformação da experiência do usuário que tem por finalidade oferecer maior acessibilidade e inclusão destinado a pacientes em processo de reabilitação. Tal como para o guiamento e liberdade de criação de atividades baseadas em jogos, especialmente na viabilidade do processo de interação do profissional de TO no momento de exposição a uma nova tecnologia implementada na rotina. Neste cenário, o TO tendo papel crucial no atendimento de crianças com PC, ao estar integrado no sistema da aplicação desktop, possui autonomia para a formulação de atividades personalizadas que são destinadas para cada indivíduo atendido, auxiliando na mensuração do seu desempenho a partir do comportamento explicitado em reação aos estímulos, estes oriundos do estabelecimento de cada detalhe constituído no momento de criação de determinado jogo pelo TO.

Levando em consideração a visão técnica a respeito do desenvolvimento da aplicação desktop construída em cima da IDE, apresenta-se ferramentas fundamentais para a projeção, permeado pela ênfase no compilador que concebe a conversão do que é escrito em termos de programação para um formato executável, propiciando a capacidade de uso para o usuário através de um sistema operacional, como o Microsoft Windows. Ademais o compilador construído com a linguagem Python, além de ser uma ator na conversão, fazendo a comunicação entre hardware e software, recebe cada entrada do usuário mantendo-se conectado ao Greg Maker, um tipo de aparelho necessário para estabelecer conexão com o tapete o qual a criança com paralisia cerebral tem contato físico para responder aos estímulos proporcionados pelo jogo.

Desse modo, compreende-se o papel crucial que o compilador exerce, porém, para tornar concreto os objetivos de inclusão e acessibilidade que atendam o WCAG, que são diretrizes a respeito dos conteúdos presentes, pois o compilador não atende estes aspectos sozinho. Sendo assim, é necessário características visuais que compõem a aplicação desktop que garantam um sistema intuitivo e de fácil manejo. Para isso é gerado a possibilidade de navegar facilmente e de produzir atividades jogáveis devido a funcionalidades específicas composto pelo chamado Electron, framework usado para criar aplicações desktop, sendo combinado com outras tecnologias e linguagens de programação necessárias para componentes visuais e funcionais como React.js. Nesse sentido, é abordado a programação em blocos low code, estas são instruções que futuramente geram um jogo sem necessitar ter conhecimento de programação, agindo de forma simplificada para o TO cumprir suas sessões.

Em virtude disso, o desenvolvimento e a implementação da aplicação desktop revela um avanço tecnológico na maneira como a terapia é conduzida para pacientes com paralisia cerebral. Ao personalizar atividades, promover interações mais significativas e garantir acessibilidade sanando a necessidade de cada indivíduo, não apenas facilita o trabalho do profissional de TO, mas também abre portas para uma reabilitação mais eficaz e inclusiva. Os resultados obtidos com a aplicação refletem não apenas a eficiência técnica, mas, acima de tudo, através de testes diretos de usabilidade que verificaram as principais funcionalidades que correspondem ao alcance do propósito, fazendo jus em aumentar a qualidade de vida e o progresso dos pacientes atendidos.

## 4. Conclusão


Este trabalho teve como objetivo analisar o desenvolvimento de um compilador e de um Ambiente de Desenvolvimento Integrado (IDE) dedicados à Tecnologia Assistiva (TA), visando resolver um problema identificado pela AACD: a estimular pessoas que enfrentam leves desordens neurológicas com uso de tecnolgia. Sendo, desenvolvida uma IDE para personalização das sessões terapêuticas, criando um compilador, e utilizando o Gregmaker para facilitar a comunicação entre o tapete e a plataforma.

Através deste artigo, compreendemos a escassez e o alto custo de ferramentas de tecnologias assistivas. Destacamos a possibilidade de inovação ao oferecer uma solução acessível e de fácil uso para terapeutas ocupacionais, abrangendo uma faixa etária de crianças que, devido às limitações de adaptação dessas tecnologias, não têm contato com as mesmas. Isso propicia uma terapia mais eficiente e acessível.

A plataforma desenvolvida tem como objetivo facilitar o uso do compilador e do tapete sensorial, garantindo que a terapeuta ocupacional, mesmo com baixo nível de conhecimento em tecnologias, consiga utilizar essas ferramentas para elaborar uma sessão de terapia personalizada para o paciente. Foram implementadas funções específicas para facilitar o uso diário dessas ferramentas.

Em resumo, o tapete sensorial, a IDE (Ambiente de Desenvolvimento Integrado) e a plataforma destacam a criação de tecnologias acessíveis e eficazes, contribuindo para a reabilitação de pacientes e atendendo a públicos que atualmente não têm acesso à tecnologia, além de permitir uma maior personalização para terapeutas ocupacionais.

Portanto, recomenda-se, em trabalhos futuros, o aprimoramento da IDE, com a adição de novas funcionalidades integráveis a outros sistemas embarcados, visando expandir essas soluções para públicos com diversas desordens neurológicas.


## Referências 

ALVES, A. C. J.; EMMEL, M. L. G.; MATSUKURA, T. S. Formação e prática do terapeuta ocupacional que utiliza tecnologia assistiva como recurso terapêutico. Revista de Terapia Ocupacional da Universidade de São Paulo, [S. l.], v. 23, n. 1, p. 24-33, 2012. DOI: 10.11606/issn.2238-6149.v23i1p24-33. Disponível em: https://www.revistas.usp.br/rto/article/view/46909. Acesso em: 12 dez. 2023.

BERSCH, R. Introdução à tecnologia assistiva, 2018. Porto Alegre: CEDI, 21. Disponível em: https://www.assistiva.com.br/Introducao_Tecnologia_Assistiva.pdf. Acesso em 12 dez. 2023.

CALHEIROS, D. dos S.; MENDES, E. G.; LOURENÇO, G. F. Considerações acerca da tecnologia assistiva no cenário educacional brasileiro. Revista Educação Especial, [S. l.], v. 31, n. 60, p. 229–244, 2018. DOI: 10.5902/1984686X18825. Disponível em: https://periodicos.ufsm.br/educacaoespecial/article/view/18825. Acesso em: 12 dez. 2023.

NAZARI, A. C. G & Gomes, M. A. (2017). Tecnologia Assistiva (TA): do conceito a legislação–discutindo a TA enquanto política de educação inclusiva que contribui na formação e inclusão de pessoas com deficiência. In V CONGRESSO DE PSICOPEDAGOGIA ESCOLAR EI ENCONTRO DE PESQUISADORES EM PSICOPEDAGOGIA ESCOLAR (pp. 1-16). Acesso em 12 dez. 2023.

NOSCHANG, F. L. et al., Portugol Studio: Uma IDE para Iniciantes em Programação, 2014. Disponível em: https://sol.sbc.org.br/index.php/wei/article/view/10954/10824. Acesso em: 8 dez. 2023.

PETRY, J. R.; MAFALDA, C. G. O.; ZANGEROLAMI, Y. E.; WIEBBELLING, G. D. S.; PEREIRA, M. B.; TROST, B. E. TECNOLOGIA ASSISTIVA: TAPETE SENSORIAL PARA CRIANÇAS AUTISTAS. Salão do Conhecimento, [S. l.], v. 4, n. 4, 2018. Disponível em: https://publicacoeseventos.unijui.edu.br/index.php/salaoconhecimento/article/view/10476. Acesso em: 9 dez. 2023.

ZILLI, F. (2013). Revisão sistêmica dos procedimentos da terapia ocupacional na paralisia cerebral. Revista Baiana de Terapia Ocupacional (inativa/apenas arquivo), 2(1), 2013. Disponível em: https://www5.bahiana.edu.br/index.php/terapiaocupacional/article/view/182/210. Acesso em: Acesso em: 9 dez. 2023.