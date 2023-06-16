<h1 align="center"> <img src="logo_redes_neurais2.PNG" style="width:530px;height:220px"/> 
</h1>

## Introdução :brain:
<details>
    
__<summary>Aprendizado de Máquina e Redes Neurais</summary>__

Machine learning (aprendizado de máquina) é um campo da inteligência artificial que se concentra em desenvolver algoritmos e modelos capazes de aprender padrões e fazer previsões a partir de dados. Ele abrange uma ampla gama de técnicas e abordagens, incluindo redes neurais. Já redes neurais são modelos computacionais inspirados no funcionamento do cérebro humano. Elas são uma abordagem específica de aprendizado de máquina que utiliza redes de neurônios interconectados para processar informações e realizar tarefas de aprendizado.
    
</details>

<details>
    
__<summary>Quais são as vantagens e limitações do uso de Redes Neurais?</summary>__
    
Ao considerar as vantagens das redes neurais, podemos destacar sua capacidade de aprender e modelar relações complexas e não lineares entre os dados. Elas são capazes de lidar com diferentes tipos de problemas, como classificação, regressão, processamento de linguagem natural e visão computacional. Além disso, as redes neurais são robustas em lidar com ruídos e dados incompletos, sendo capazes de trabalhar com grandes volumes de dados. Elas também têm a capacidade de aprendizado contínuo, permitindo a incorporação de novas informações sem a necessidade de treinar o modelo do zero.

No entanto, o uso de redes neurais também apresenta algumas limitações. Elas exigem um grande volume de dados de treinamento para obter resultados robustos e podem ser computacionalmente intensivas, demandando recursos de hardware significativos. A interpretação e explicação dos resultados gerados por redes neurais podem ser desafiadoras, devido à sua complexidade e ao raciocínio não linear do modelo. Além disso, as redes neurais podem sofrer de overfitting, ou seja, ajustar-se muito bem aos dados de treinamento, mas não generalizar bem para dados não vistos. A escolha adequada da arquitetura da rede neural e dos hiperparâmetros também é um desafio e requer conhecimento especializado.
    
</details>

<details>
    
__<summary>Exemplos de problemas do mundo real que podem ser resolvidos usando redes neurais</summary>__
    
No mundo real, as redes neurais têm sido aplicadas com sucesso em diversos problemas. Por exemplo, elas são usadas para reconhecimento de imagens e objetos em visão computacional, classificação de textos e análise de sentimentos em processamento de linguagem natural, previsão de demanda em problemas de previsão, detecção de fraudes em transações financeiras, sistemas de recomendação personalizada, diagnóstico médico e análise de imagens médicas, controle de robôs e sistemas autônomos, entre outros. Esses exemplos mostram a ampla aplicabilidade das redes neurais em diversos setores e domínios, fornecendo soluções para problemas complexos que envolvem dados e padrões.
    
</details>

## Conteúdo :card_index_dividers:

<details>
    
__<summary>Glossário :page_with_curl:</summary>__


- __*Neurônio*:__ É uma unidade básica de processamento que recebe entradas, realiza cálculos e produz uma saída. Inspirado no funcionamento dos neurônios biológicos do cérebro humano, um neurônio artificial é projetado para realizar operações matemáticas.

- __*Camada Oculta*:__ Em redes neurais, a camada oculta refere-se a uma ou mais camadas intermediárias entre a camada de entrada e a camada de saída. Os neurônios nessas camadas ocultas não estão diretamente conectados às entradas ou às saídas da rede. Eles realizam cálculos e transformações nos dados de entrada, ajudando a capturar e representar características mais complexas e abstratas dos dados. A presença de camadas ocultas permite que a rede neural aprenda representações hierárquicas e não lineares dos dados, aumentando sua capacidade de generalização.

    
- __*Camada Input*:__ A camada de entrada é a primeira camada de uma rede neural. Ela recebe os dados de entrada e repassa esses dados para a próxima camada da rede. Cada neurônio nessa camada está associado a um atributo ou característica específica dos dados de entrada. Cada valor de entrada é propagado pelos neurônios da camada de entrada para as camadas seguintes, onde serão processados.
    
    
- __*Camada Output*:__ A camada de saída é a última camada de uma rede neural. Ela produz a saída final da rede, que é o resultado do processamento das informações fornecidas pelos neurônios nas camadas anteriores. A quantidade de neurônios nessa camada depende do tipo de problema que a rede neural está sendo usada para resolver. Por exemplo, em problemas de classificação binária, pode haver um único neurônio na camada de saída, enquanto em problemas de classificação multiclasse, pode haver vários neurônios, um para cada classe possível.
    
    
- __*Bias (Viés)*:__ O bias, também conhecido como viés, é um parâmetro adicional em cada neurônio de uma rede neural. Ele representa um valor fixo que é adicionado à soma ponderada das entradas antes da aplicação da função de ativação. O bias permite que a rede neural faça ajustes na ativação dos neurônios, adicionando um termo de deslocamento à decisão de ativação. Isso é útil quando os dados não estão centralizados em torno de zero ou quando há uma preferência para ativar ou desativar os neurônios.
    
    
- __*Backpropagation*:__ O backpropagation é um algoritmo utilizado para treinar redes neurais. Ele é usado para calcular os gradientes e ajustar os pesos e os biases da rede com base no erro entre as saídas previstas e as saídas desejadas. O algoritmo funciona propagando o erro da camada de saída para as camadas anteriores da rede, calculando os gradientes por meio da regra da cadeia e atualizando os pesos e biases com base nesses gradientes. O backpropagation é fundamental para o aprendizado das redes neurais, permitindo que elas se ajustem aos dados de treinamento e melhorem suas previsões ao longo do tempo.
    
    
- __*Forward Pass*:__ O forward pass, também conhecido como propagação direta, é o processo de passar os dados de entrada por todas as camadas da rede neural, a partir da camada de entrada até a camada de saída. Durante o forward pass, cada neurônio recebe os valores de entrada, realiza uma combinação linear das entradas ponderadas pelos pesos, adiciona o bias e aplica uma função de ativação para gerar a saída. Esse processo é repetido camada por camada até que a saída final seja produzida.
    
    
__*Gradiente Local*:__ O gradiente local refere-se ao gradiente da função de ativação em relação à entrada de um neurônio. Em cada neurônio de uma rede neural, a função de ativação é aplicada à combinação linear das entradas ponderadas pelos pesos. O gradiente local indica como a saída do neurônio deve ser ajustada para reduzir o erro durante o processo de treinamento. É usado no cálculo dos gradientes durante o backpropagation para atualizar os pesos e biases da rede. Ele desempenha um papel crucial na determinação da direção e magnitude das alterações a serem feitas nos parâmetros da rede para melhorar o desempenho do modelo.
    
</details>