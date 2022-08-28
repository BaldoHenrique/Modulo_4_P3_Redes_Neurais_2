# Modulo_4_P3_Redes_Neurais_2
Curso Ciência de dados da Blue Edtech - AExtração de características e classificação de folhas de uva - Grapevine Leaves Image Dataset

# Projeto 3 - Extração de características e classificação de folhas de uva - Grapevine Leaves Image Dataset

## Entrega
  - O projeto deve ser entregue até o domingo da 4ª semana de aula, envie o link do GitHub ou HTML na atividade no Moodle.
  - O prazo máximo é segunda-feira da 4ª semana de aula, valendo 20% a menos da nota.

## Dados do Certificado
  - Linguagem: Python
  - Tecnologias: Pandas, Numpy, Tensorflow, Keras, PIL, Matplotlib e Sklearn
  - Carga horária: 12 horas

## Grapevine Leaves Image Dataset - Kaggle
  - Este é um conjunto de dados de imagens de folhas de uva. A análise das espécies de folhas de uva são importantes para determinar o preço e o sabor. Encontrar as características a partir de uma folha pode auxiliar a saber o valor e a qualidade de uma safra.

## Preparação do ambiente
  - Faça o download e carregue o dataset Grapevine Leaves Image Dataset.

## Exercícios
  - Questão 1) Escolha uma rede pré-treinada em imagens para fazer transferência de aprendizado por meio de fine-tuning (2,5 pontos):
     - a) Determine quais camadas serão acrescentadas, o tamanho do batch, a quantidade de épocas e a forma de treinamento (fit ou train_on_batch) (2 pontos).
     - b) Compare a predição diretamente pela rede com a extração de características (0,5 ponto).
  - Questão 2) Considerando a mesma rede pré-treinada do exercício anterior, faça fine-tuning congelando algumas camadas. Determine a quantidade de camadas a serem congeladas, indique o setup escolhido e compare o resultado obtido em relação ao fine-tuning convencional. (2,5 pontos)
  - Questão 3) Considerando a mesma rede pré-treinada do primeiro exercício, faça fine-tuning com Data Augmentation. Explore essas técnicas e verifique se sua utilização melhora a performance do modelo. Não fique restrito às técnicas de exemplo. Estude as demais funções existentes no pacote ImageGenerator. (2,5 pontos)
  - Questão 4) Interpretação dos resultados (2,5 pontos):
     - a) Baseando-se nos experimetnos anteriores, indique a melhor solução para este conjunto de dados.
     - b) Apresente gráficos e dados comparativos que justifiquem suas escolhas.

## Referência
Koklu, M., Unlersen, M. F., Ozkan, I. A., Aslan, M. F., & Sabanci, K. (2022). A CNN-SVM study based on selected deep features for grapevine leaves classification. Measurement, 188, 110425. Doi:https://doi.org/10.1016/j.measurement.2021.110425
