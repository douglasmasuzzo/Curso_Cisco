# **CURSO : INTRODUÇÃO À CIÊNCIA DE DADOS** #

>> ## Módulo02 - Coleta e Armazenamento de Dados ( **2.0.1 - Introdução** ) ##

## Descrição ##
 O módulo introduzirá as características associadas a **Big Data**, o **PipeLine** e as técnicas de **Gestão de Big Data**. 

 - **Tópico - Noções básicas de Big Data**
    - _Descrever o Big Data e seus benefícios_

 - **Tópico - Noções básicas sobre Gerenciamento de Big Data**
    - _Descreva o fluxo de dados por meio de pipelines_

----------------------------------------------------------------------------------

>> ## Módulo02 - Coleta e Armazenamento de Dados ( **2.0.2 - Definição de Big Data** ) ##

## Descrição ##
 Os analistas de dados apresentam os conceitos de análise e a importância das visualizações. Agora é hora de trabalhar com os engenheiros de dados da empresa para aprender sobre Big Data e o papel que os engenheiros desempenham na criação, manutenção e garantia de que a infraestrutura de dados da corporação esteja disponível e confiável.
 
 **Big Data** é um termo usado para descrever os grandes volumes de dados digitais gerados, coletados e processados. O termo big data descreve dados que estão se movendo rapidamente, são simplemente muito grandes ou complexos para serem armazenados, processados ou analisados com aplicações tradicionais de armazenamento e análise de dados. Alguns exemplos de Big Data incluem dados gerados por postagens em contas de Mídia Social, como _Facebook, Twitter e Amazon_.

 O tamanho é apenas uma das características que definem o termo. Outros critérios incluem a velocidade dos dados gerados e a variedade de dados coletados e armazenados.

----------------------------------------------------------------------------------

>> ## Módulo02 - Coleta e Armazenamento de Dados ( **2.0.3 - Características** ) ##

## Descrição ## 
 As características mudam a forma como os dados são coletados, transmitidos, armazenados e acessados. Clique em cada quadrante na figura abaixo para ler sobre os *4 V's* do termo e os desafios enfrentado por engenheiros de infraestrutura de dados. 


### _**Volume** - Escala de Dados_ ###
 O volume descreve a quantidade de dados transportados e armazenados. De acordo com especialistas da **International Data Corporation ( IDC )**, descobrir maneiras de processas as quantidades crescentes de dados gerados a cada dia é um desafio. 
 Eles preveem que o volume de dados aumentará a uma taxa de crescimento anual composta de 23% nos próximos cinco anos. Embora os sistemas de armazenamento de dados tradicionais possam, em teoria, lidar com grande quantidades de dados, eles estão lutando para acompanhar as demanadas de volume de Big Data.

### _**Variedade** - Formato de Dados_ ###
 A variedade descreve as muitas formas que os dados podem assumir, a maioria das quais raramente está pronta para processamento e análise. Um contribuinte significativo para o conceito são os dados não estruturados, que representam cerca de 90% dos dados coletados mundialmente.
 Esses formatos são muito complexos para as arquiteturas de **Data WareHouse** ( sistema de gerenciamento de dados ). Os Dados Não-Estruturados que compõem uma parte significativa do Big Data não se encaixam nas linhas e colunas do sistema tradicional de armazenamento de dados relacionais.

### _**Velocidade** - Fluxo de Dados_ ###
 A velocidade descreve a taxa na qual os dados são gerados. Por exemplo, os dados gerados pela Bolsa de Valores de New York por um bilhão de ações vendidas não podem ser armazenados para análise posteriormente. Devem ser analisados e relatados imediamente. 
 A infraestrutura de dados deve responder instantaneamente às demandas das aplicações que acesssam e transmitem os dados. O Big Data é dimensionado instantaneamente, e precisa corresponder e ocorrer em tempo real.

### _**Veracidade** - Incerteza de Dados_ ###
 A veracidade é o processo de impedir que dados imprecisos estraguem os conjuntos de dados. Por exemplo, quando as pessoas se increvem em uma conta online, geralmente usam informações de contato falsas.
 Muitas dessas informações imprecisas devem ser " eliminadas " dos dados antes de serem usados em análise. O aumento de veracidade na coleta de dados pode reduzir a quantidade de limpeza de dados necessária.

----------------------------------------------------------------------------------

>> ## Módulo02 - Coleta e Armazenamento de Dados ( **2.0.4 - Item Prático : Características** ) ##

### _Questões Práticas_ ###

 Agora que os engenheiros explicaram as várias características do conceito Big Data, consegue identificar qual característica está descrita em cada exemplo abaixo?

 1. _Um varejista on-line analisa os dados das classificações e avaliações dos clientes. O varejista está preocupado com o fato de que as pessoas podem ser mais propensas a fornecer avaliações se tiverem uma experiência ruim do que se tiverem uma boa experiência com um produto_.

    > Resposta : **Veracidade**

    - Correto! A veracidade é a característica que reflete a precisão dos dados coletados. O varejista está preocupado com o fato de que os dados podem não refletir com precisão a opinião da maioria dos clientes.

 2. _Um fabricante está instalando cem novos sensores para verificar se há defeitos no produto durante a produção. Os sensores farão de vinte a trinta leituras por segundo e, em seguida, deverão analisar os dados imediatamente para determinar se um problema com o equipamento ou processo está causando um defeito_
 
    > Resposta : **Velocidade**

    - Correto! A velocidade reflete a rapidez com que os dados de alta velocidade são coletados e quão rapidamente devem ser analisados para serem eficazes.  

 3. _Um estúdio de cinema está coletando feedback sobre um novo filme que estreou em um cinema tradicional e em um serviço de streaming durante a mesma semana. O feedback é coletado por meio de classificações e análises, comentários nas mídias sociais e artigos de revistas_

    > Resposta : **Varieadade**

    - Correto! Variedade significa que os dados são coletados de muitas fontes em formatos diferentes e que a maioria não é estruturada.

 4. _Uma empresa de processamento de cartão de crédito processa mais de 18 milhões de transações por dia e relata os números de conta e as informações de compra para os emissores do cartão. Todas as transações devem ser armazenadas até que a confirmação seja recebida dos emissores do cartão e as informações de saldo sejam atualizadas_
    
    > Resposta : **Volume**

    - Correto! O volume representa a grande quantidade de dados que devem ser armazenados, mesmo que temporariamente.

----------------------------------------------------------------------------------

>> ## Módulo02 - Coleta e Armazenamento de Dados ( **2.0.5 - Os possíveis benefícios do Crescimento de Dados** ) ##

## Descrição ##
 Essa explosão de dados permite que as aplicações aproveitem as tendências e comparações descobertas por meio de análise para agir, fazer recomendações e previsões confiáveis. Existem impulsionadores desse crescimento de dados, mas os mais predominantes incluem :

 - A proliferação de dispositivos na Internet das Coisas ( **IoT** )
 - Maior acesso à Internet, juntamente a Banda Larga
 - Uso de smartphones e a popularização de redes socias

### _Serviços de Saúde_ ###
 A robótica, os dispositivos médicos inteligentes, os sistemas de software integrados e as plataformas de colaboração virtual estão mudando a forma de atendimento ao paciente. Muitas dessas tecnologias orientadas por dados simplificam a vida de pacientes, médicos e administradores de serviços de saúde, realizando tarefas que normalmente são realizadas por humanos. 
 Os computadores podem detectar cânceres com precisão notável utilizando dados disponíveis em exames médicos. Esses sistemas criam mais dados a serem futuramente analisados e usados para melhorar o atendimento.

### _Varejo_ ###
 Os varejistas dependem cada vez mais dos dados gerados por tecnologias digitais para melhorar os resultados. O **Connected Mobile Experience** ( CMX ) permite que os profissionais forneçam aos consumidores, conteúdos personalizados, enquanto obtém visibilidade do comportamentdo deles em sua empresa.

### _Educação_ ###
 Na educação, os instrutores podem usar dados para identificar áreas que os alunos possuem dificuldades ou não progridem o desenvolvimento, entendendo as necessidades individuais dos alunos e projetando estratégias para um aprendizado personalizado. As escolas virtuais oferecem aos alunso, acesso aos livros didáticos, conteúdo e assistência projetada para atender às necessidades dos alunos.
