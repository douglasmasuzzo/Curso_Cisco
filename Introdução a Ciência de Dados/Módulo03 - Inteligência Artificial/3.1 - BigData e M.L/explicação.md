# **CURSO : INTRODUÇÃO À CIÊNCIA DE DADOS** #

>> ## Módulo03 - Inteligência Artificial e Aprendizagem de Máquina ( **3.1.1 - O que é Aprendizado de Máquina ( Machine Learning )?"** ) ##

## Transcrição : "O que é aprendizado de máquina ( Machine Learning )?" ##
 Está na moda hoje em dia, empresas divulgando que o aprendizado de máquina faz isso ou que o aprendizado de máquina faz aquilo fornecedores que prometem uma solução para todos os desafios de TI. A empolgação está ficando bastante intensa
 Então, o que exatamente é o aprendizado de máquina? Tradicionalmente, os computadores resolvem problemas por meio de programas ou instruções dadas a eles por um ser humano. O aprendizado de máquina significa apenas que o computador pode descobrir uma solução sem serem especificamente programados.
 Essas máquinas têm a capacidade de aprender continuamente analisando os dados e encontrando padrões, e fazem isso muito mais rápido do que um ser humano. Vamos analisar dois termos importantes do aprendizado de máquina: classificadores e algoritmos.
 Os classificadores são a base do aprendizado de máquina que categorizam as observações, enquanto os algoritmos são as técnicas que organizam e orientam os classificadores. Muitas vezes, o aprendizado de máquina requer treinamento com conjuntos de pares de perguntas e respostas corretas que permite que o classificador e os algoritmos façam um ótimo trabalho.
 Vamos olhar um exemplo para ver como funciona. Os classificadores analisam padrões de dados específicos, não narizes ou olhos reais. E com treinamento suficiente, eles podem escolher sua foto entre milhões de opções. Então, como usamos o aprendizado de máquina em segurança?
 Imagine um pipeline de análise que utiliza centenas de classificadores e algoritmos de aprendizado de máquina, todos trabalhando juntos, analisando milhões de pontos de dados e eventos internos e externos. 
 O pipeline identifica e separa atividades suspeitas maliciosas das normais. Em seguida, é organizado em eventos específicos e, posteriormente, combinado com contexto acionável para as equipes de segurança. E faz tudo isso na velocidade da máquina. Super incrível, não é?

-----------------------------------------------------------------------------

>> ## Módulo03 - Inteligência Artificial e Aprendizagem de Máquina ( **3.1.2 - Item Prático : O que é Aprendizado de Máquina ( Machine Learning )?"** ) ##

### _Questões Práticas_ ###
 A aprendizagem de máquina tornou-se cada vez mais popular entre empresas e organizações em todas as indústrias para melhorar a eficiência e a produtividade. Use a Internet para pesquisar casos de uso de aprendizado de máquina. Identifique cinco casos de uso que abrangem diferentes setores ou aplicações e use o espaço abaixo para discutir as descobertas.


 1. _Saúde : Diagnósticos por Imagens_

    > Resposta : **Na medicina, algoritmos de Visão Computacional (um subcampo do ML) são treinados com milhões de exames de imagem para identificar padrões que o olho humano pode deixar passar.**

 2. _Financias : Detecção de Fraudes_

    > Resposta : **O setor bancário utiliza o ML para proteger transações. Diferente de sistemas antigos baseados em regras rígidas, o ML aprende o comportamento habitual de cada usuário.**

 3. _Varejo e E-commerce : Sistemas de Recomendações_

    > Resposta : **O algoritmo analisa seu histórico de compras, termos de busca e até o tempo que você passa olhando para uma imagem. Ele então cruza esses dados com usuários que têm perfis similares aos seus.**

 4. _Agronegócio : Agricultura de Precisão_

    > Resposta : **Sensores de solo e drones coletam dados sobre umidade, nutrientes e pragas. Modelos de ML processam esses dados para ditar exatamente onde e quanto fertilizante aplicar.**

 5. _Indústria : Manutenção Preditiva_

    > Resposta : **ensores de vibração e calor instalados em equipamentos enviam dados constantes para um modelo de ML. O algoritmo identifica padrões de desgaste que precedem uma falha técnica.**

-----------------------------------------------------------------------------

>> ## Módulo03 - Inteligência Artificial e Aprendizagem de Máquina ( **3.1.3 - Tipos de Análise de Aprendizado de Máquina"** ) ##

## Descrição ##
 O aprendizado de máquina engloba diferentes algoritmos ou modelos com ampla aplicabilidade, enquanto outros são adequados para aplicações específicas. O aprendizado de máquina é dividido em três abordagens de modelo de aprendizado primário: supervisionado, não supervisionado e reforço. 
 Cada modelo é diferente no treinamento; cada um tem seus pontos fortes e enfrenta diferentes tarefas ou problemas. Ao escolher um modelo de aprendizado de máquina para implantação, uma empresa precisa entender os dados disponíveis e o problema a ser resolvido. Selecione os exemplos abaixo para saber mais sobre cada tipo de modelo de aprendizado de máquina.


### _Supervisionado_ ###
 
 Os algoritmos de aprendizado de máquina supervisionado são os mais usados para análise preditiva. A aprendizagem supervisionada requer interação humana para rotular dados lidos para um aprendizado supervisionado preciso. No aprendizado supervisionado, o modelo é ensinado por meio de exemplos usando conjuntos de dados de entrada e saída processados por especialistas humanos, geralmente cientistas de dados.
 O modelo aprende as relações entre os dados de entrada e saída e, em seguida, utiliza essas informações para formular previsões com base em novos conjuntos de dados. Por exemplo, um modelo de classificação pode aprender a identificar plantas após ser treinado com um conjunto de dados de imagens devidamente rotuladas com a espécie da planta e outras características identificadoras.  

 Os métodos de aprendizado de máquina supervisionado geralmente resolvem problemas de regressão e classificação:
 
 - Problemas de regressão envolvem a estimativa das relações matemáticas entre uma variável contínua e uma ou mais outras variáveis. Essa relação matemática pode calcular os valores de uma variável desconhecida, de acordo com os valores conhecidos das outras. Exemplos de problemas que usam a regressão incluem estimar a posição e a velocidade de um carro usando GPS, prever a trajetória de um tornado usando dados climáticos ou prever o valor futuro de uma ação usando dados históricos e outros dados.  

 - Os problemas de classificação consistem em uma variável desconhecida discreta. Normalmente, o problema envolve estimar qual amostra específica pertence a um conjunto de classes predefinidas. Exemplos de classificação são filtrar e-mail em spam ou não spam, diagnosticar patologias de exames médicos ou identificar rostos em uma imagem.  

### _Sem Supervisão_ ###
 
 Os algoritmos de aprendizado de máquina não supervisionados não exigem especialistas humanos, mas descobrem padrões nos dados de forma autônoma. O aprendizado não supervisionado lida principalmente com dados não rotulados. O modelo deve funcionar por conta própria para encontrar padrões e informações. Exemplos de problemas resolvidos com métodos não supervisionados são clustering e associação:

 - Métodos de clustering : Clustering é o agrupamento de dados que têm características semelhantes. Ele ajuda a segmentar os dados em grupos e analisa cada um para encontrar padrões. Por exemplo, algoritmos de agrupamento identificam grupos de usuários com base em seu histórico de compras online e, em seguida, enviam anúncios direcionados a cada membro.  
 
 - Métodos de associação : A associação consiste em descobrir grupos de itens frequentemente observados juntos. Os varejistas on-line usam associações para sugerir compras adicionais a um usuário com base no conteúdo do carrinho de compras.  

### _Reforço_ ###

 O aprendizado por reforço ensina a máquina por tentativa e erro usando o feedback de suas ações e experiências, também conhecido como aprendizado com os erros. Isso envolve atribuir valores positivos para resultados desejados e valores negativos para efeitos indesejados.
 predO resultado são as soluções ideais; o sistema aprende a evitar resultados adversos e a buscar o positivo. Aplicações práticas de aprendizado por reforço incluem a construção de inteligência para jogar videogames, bem como em robótica e automação industrial.

-----------------------------------------------------------------------------

>> ## Módulo03 - Inteligência Artificial e Aprendizagem de Máquina ( **3.1.4 - Item Prático : Tipos de Aprendizado de Máquina"** ) ##

### _Questões Práticas_ ###
 Selecione o modelo de aprendizado de máquina correto para cada cenário.

 1. _"Um robô que cria um sistema de controle adaptativo para si mesmo e aprende com suas próprias experiências e comportamentos"_

   > Resposta : **Aprendizado de Máquina - Reforço**

   - Correto! Uma característica chave do aprendizado de máquina por reforço é que ele aprende com os erros. O sistema aprende por tentativa e erro para encontrar soluções. Neste exemplo, o sistema está criando um sistema de controle adaptável aprendendo, por meio de tentativa e erro, com suas próprias experiências.

 2. _"Um sistema de reconhecimento facial que identifica e categoriza as características faciais usando um grande conjunto de dados de treinamento processado por humanos"_

   > Resposta : **Aprendizado de Máquina - Supervisionado**

   - Correto! O aprendizado supervisionado exige que um supervisor, geralmente um humano, forneça os conjuntos de dados para treinar o algoritmo para classificar os dados com precisão. Neste exemplo, um algoritmo de aprendizado supervisionado para classificar os recursos faciais usando um conjunto de dados fornecido pelo supervisor. 

 3. _"Um sistema de recomendação para agrupar usuários com padrões de visualização semelhantes e recomendar conteúdo semelhante"_

   > Resposta : **Aprendizado de Máquina - Sem Supervisão** 

   - Correto! O aprendizado não supervisionado usa algoritmos de aprendizado de máquina para identificar padrões nos dados que não foram rotulados anteriormente. Os próprios algoritmos identificam correlações ou tendências nos dados sem a entrada dos cientistas de dados. Neste exemplo, o algoritmo está procurando padrões no comportamento de visualização de filmes dos clientes para que possam ser agrupados com outros clientes com comportamento de visualização semelhante.

-----------------------------------------------------------------------------

>> ## Módulo03 - Inteligência Artificial e Aprendizagem de Máquina ( **3.1.5 - O Processo de Aprendizado de Máquina"** ) ##

## Descrição ##
 O desenvolvimento de uma solução de aprendizado de máquina raramente é um processo linear. Várias etapas de tentativa e erro são necessárias para ajustar a solução. Os detalhes de cada etapa realizada pelos cientistas de dados dos Data Crunchers, enquanto trabalham no novo modelo de identificação e erradicação de ervas daninhas, são os seguintes etapas:

 1. _Preparação de dados_ 
      > Execute procedimentos de limpeza de dados, como transformação em um formato estruturado e remoção de dados ausentes e observações com ruído/corrompidas.   

 2. _Dados de aprendizado_
      > Criar um conjunto de dados de aprendizado usado para treinar o modelo. 

 3. _Dados de teste_
      > Crie um conjunto de dados de teste usado para avaliar o desempenho do modelo. Execute esta etapa apenas no caso de aprendizado supervisionado.   

 4. _Loop do processo de aprendizagem : **Seleção**_
      > Um algoritmo é escolhido de acordo com o problema. Dependendo do algoritmo selecionado, podem ser necessárias etapas adicionais de pré-processamento.

 5. _Loop do processo de aprendizagem : **Avaliação**_ 
      > O desempenho desse algoritmo selecionado é avaliado nos dados de aprendizado. Se o algoritmo e o modelo atingirem um desempenho aceitável nos dados de aprendizado, a solução validará os dados de teste. Caso contrário, repita o processo de aprendizado com um novo modelo e algoritmo propostos.
      
 6. _Avaliação do modelo : **Teste**_ 
 
      > A solução nos dados de teste. Os desempenhos nos dados de aprendizagem não são necessariamente transferíveis para os dados de teste. Quanto mais complexo e ajustado for o modelo, maiores serão as chances de ele se tornar propenso a overfitting, o que significa que ele não pode ter um desempenho preciso em relação a dados não vistos. O ajuste excessivo pode resultar no retorno ao processo de aprendizado do modelo.   

 7. _Implementação do modelo_ 
      > Depois que o modelo atingir um desempenho satisfatório nos dados de teste, implemente o modelo. Implementar o modelo significa realizar as tarefas necessárias para dimensionar a solução de aprendizado de máquina para Big Data.  

-----------------------------------------------------------------------------

>> ## Módulo03 - Inteligência Artificial e Aprendizagem de Máquina ( **3.1.6 - Item Prático : O Processo de Aprendizado de Máquina"** ) ##

### _Questões Práticas_ ###
 Os cientistas de dados que trabalham com nosso cliente, a AgroTech Robotics, revisaram o processo usado para criar o modelo de aprendizado de máquina. Eles querem que você documente o processo, incluindo todas as etapas necessárias para concluir o projeto. Você está pronto para a tarefa?

 1. _Dados de Aprendizado_
   
   > Resposta : **Conjunto de Dados de Aprendizagem criado para treinar o modelo**

 2. _Dados de Teste_

   > Resposta : **Conjunto de Dados de Teste criado para avaliar o modelo**

 3. _Loop do Processo de Aprendizagem - Seleção_

   > Resposta : **O algoritmo é escolhido**

 4. _Loop do Processo de Aprendizagem - Avaliação_

   > Resposta : **O algoritmo é avaliado com base nos dados de aprendizagem**

 5. _Avaliação do Modelo_

   > Resposta : **A solução é avaliada em relação aos dados de teste**

 6. _**Etapas**_
   - Preparação de dados com procendimentos de limpeza de dados
   - Criação de um conjunto de dados de aprendizado usado para treinar o modelo e testar um conjunto de dados para avaliar o modelo 
   - O algoritmo é escolhido de acordo com o problema a ser resolvido
   - O algoritmo é avaliado nos dados de aprendizagem
   - A solução é testada em relação aos dados de teste
   - O modelo é implementado

-----------------------------------------------------------------------------

>> ## Módulo03 - Inteligência Artificial e Aprendizagem de Máquina ( **3.1.7 - Treinando Máquinas para Reconhecimento de Padrões"** ) ##

## Descrição ##

 Anteriormente, você aprendeu que aprendizado de máquina é um subconjunto de inteligência artificial. Inteligência artificial é o conceito de que um sistema pode aprender com os dados, identificar padrões e tomar decisões com pouca ou nenhuma intervenção humana. O aprendizado de máquina tem muitas aplicações valiosas no campo da análise de dados. Uma aplicação essencial é o reconhecimento de padrões.

 O reconhecimento de padrões utiliza algoritmos de aprendizado de máquina para identificar padrões em dados digitais. Esses padrões são aplicados a diferentes conjuntos de dados com o objetivo de reconhecer padrões iguais ou semelhantes nos novos dados. Os dados podem estar contidos em muitos formatos diferentes, como texto, fotografias ou vídeos. Por exemplo, ao fazer referência a classes de aves, uma descrição de uma ave seria um padrão. Os tipos podem ser pardais, tordos ou tentilhões, entre outros. Usando visão computacional, tecnologias de processamento de imagem e reconhecimento de padrões, podemos extrair padrões específicos de imagens de aves neste exemplo e compará-los com fotos de aves armazenadas em um banco de dados.

 O reconhecimento de padrões usa o conceito de aprendizado para classificar dados com base nas informações estatísticas obtidas com os padrões e suas representações. O aprendizado permite que os sistemas de reconhecimento de padrões sejam "treinados" e adaptáveis para fornecer resultados mais precisos. Ao treinar o sistema de reconhecimento de padrões, uma parte do conjunto de dados prepara o sistema, e o restante testa a precisão do sistema. Conforme mostrado na figura abaixo, o conjunto de dados é dividido em dois grupos: treinar o modelo e testar o modelo. O conjunto de dados de treinamento é usado para criar o modelo e consiste em cerca de 80% dos dados. Ele contém o conjunto de imagens usadas para treinar o sistema. O conjunto de dados de teste consiste em cerca de 20% dos dados e mede a precisão do modelo. Por exemplo, se o sistema que identifica categorias de aves puder identificar corretamente sete em cada dez aves, a precisão do sistema será de 70%.

 Os algoritmos de reconhecimento de padrão podem ser aplicados a diferentes tipos de dados digitais, incluindo imagens, textos ou vídeos, e podem ser usados para automatizar e resolver totalmente problemas analíticos complicados. As aplicações e os casos de uso para reconhecimento de padrões são praticamente ilimitados. Alguns exemplos incluem:

  - _Segurança Móvel_ : Identificação de impressões digitais ou reconhecimento facial para obter acesso a um smartphone.  

  - _Engenharia_ : Reconhecimento de fala por sistemas de assistente digital, como Alexa, Google Assistant e Siri.  

  - _Geologia_ : Detecção de tipos específicos de rochas e minerais e interpretação de padrões temporais em gravações de matrizes sísmicas. 

  - _Biomédica_ : Uso de padrões biométricos para identificar células tumorais e cancerígenas no corpo.

-----------------------------------------------------------------------------

>> ## Módulo03 - Inteligência Artificial e Aprendizagem de Máquina ( **3.1.8 - Item Prático : Treinando Máquinas para Reconhecimento de Padrões"** ) ##

### _Questões Práticas_ ###

 O aprendizado de máquina cria modelos preditivos com base nos dados e aprende com eles. No ML, os dados são divididos em dois conjuntos, e o primeiro é conhecido como ~~()~~ de dados e é usado para criar o modelo e consiste em cerca de 80% do conjunto de dados.
 Depois que o modelo de aprendizado de máquina é criado, sua precisão deve ser medida. Para esse processo, o sistema realiza ~~()~~ de dados, que consistem nos outros 20% dos dados, para avaliar o desempenho do modelo e ajustá-lo ou otimizá-lo para obter melhores resultados.

  > Resposta : **Treinamento de Dados**

  > Resposta : **Teste (Depuração) de Dados**

  - Correto! O reconhecimento de padrões exige que o sistema “aprenda” a fornecer resultados precisos. A fase de aprendizado é a mais crítica para determinar o quão bem o sistema se sai com os dados fornecidos a ele. Para o processo de aprendizagem, todo o conjunto de dados é dividido em dois conjuntos. O primeiro conjunto é o conjunto de treinamento usado na criação e no treinamento do modelo. O segundo conjunto, o conjunto de teste, é usado para testar o modelo e verificar se ele produz a saída correta. Geralmente, o conjunto de treinamento consiste em 80% dos dados e o conjunto de teste consiste nos outros 20%.
