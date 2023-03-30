# UNICAMP - Projeto

## Parte 1 - Máquinas de Vetores de Suporte (SVM)

Esta etapa do projeto verificará o funcionamento de máquinas de vetores de suporte, tanto com kernel linear quanto Gaussiano. O arquivo dado1.mat contém um conjunto de exemplos, com 2 atributos, e linearmente separáveis. Quando este dado é carregado, terá acesso às variáveis X (atributos) e y (classes). Queremos observar a fronteira de decisão, variando C, além de estudar a influência de outliers no processo, conforme C varia.
Já o arquivo dado2.mat contém dados que não são linearmente separáveis e, por isso, deverá fazer uso de SVM com kernels. Agora, além das variáveis X e y, terá acesso também a Xval e yval, que serão usados para validação. Usaremos o conjunto de validação para determinar os hiperparâmetros ideias (C e σ). Feito isso, queremos, mais uma vez, estudar a fronteira de decisão para cada caso de variação dos hiperparâmetros


## Parte 2 - Análise de Componentes Principais (PCA)

Uma das aplicações mais interessantes e surpreendentes de análise de componentes principais é no reconhecimento facial (eigenfaces). Sendo assim, o arquivo dado3.mat  possuirá, no atributo X, matrizes de 32 x 32, convertidas em um vetores de 1024 componentes, em cada linha, as quais representam imagens de faces em tons de cinza. Devemos buscar as eigenfaces e entender qual o impacto ao utilizar apenas algumas deles para geração de uma imagem.

Resultados do projeto estão no arquivo "SVM e PCA.pdf"
