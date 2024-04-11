# Dimensionalidade_PCA_KPCA
Pasta de estudo e aplicação sobre PCA e KPCA

PCA (Análise de Componentes Principais):
PCA é uma técnica de redução de dimensionalidade que é comumente usada para encontrar padrões nos dados, identificar as direções (ou componentes) que maximizam a variância dos dados e projetar os dados em um novo espaço dimensional com menos dimensões. Essencialmente, o PCA procura uma transformação linear dos dados originais para um novo conjunto de variáveis não correlacionadas chamadas de componentes principais.

KPCA (Análise de Componentes Principais Kernelizada):
KPCA é uma extensão do PCA que permite lidar com dados não linearmente separáveis. Ele opera no espaço de características mapeando os dados originais para um espaço de características de maior dimensão, onde é mais provável que os dados sejam linearmente separáveis. Isso é alcançado por meio do uso de uma função kernel, que calcula o produto escalar entre os pares de pontos no espaço de entrada, permitindo assim que o PCA seja aplicado em um espaço de características mais complexo.

conceitos matemáticos:

PCA:

Cálculo da Média: O PCA começa calculando a média de cada variável nos dados.
Matriz de Covariância: Em seguida, ele calcula a matriz de covariância dos dados, que descreve como as variáveis nos dados estão correlacionadas entre si.
Autovalores e Autovetores: O PCA então calcula os autovalores e autovetores da matriz de covariância. Os autovetores representam as direções principais dos dados, enquanto os autovalores indicam a importância dessas direções.
Seleção de Componentes Principais: Finalmente, o PCA seleciona os autovetores correspondentes aos maiores autovalores como os componentes principais, que formam uma base para o novo espaço dimensional.
KPCA:

Mapeamento Não Linear: O KPCA começa mapeando os dados originais para um espaço de características de maior dimensão usando uma função kernel, como o kernel RBF (Radial Basis Function).
Cálculo do PCA: Em seguida, ele aplica o PCA neste novo espaço de características para encontrar os componentes principais.
Projeção dos Dados: Os dados são projetados nos componentes principais encontrados, resultando em uma representação de menor dimensionalidade que preserva a estrutura não linear dos dados originais.



Leitura: https://medium.com/pursuitnotes/day-47-kernel-pca-edfcedae3b64
