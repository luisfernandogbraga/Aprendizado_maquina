# Projeto de Aprendizado de Máquina com RandomForestClassifier

![McMurdo-Pinguine-600x332](https://github.com/luisfernandogbraga/Aprendizado_maquina/assets/134460985/043b078f-ace0-4b53-8a66-26506fe58ec8)

- Descrição do Projeto
  
Este é um projeto de aprendizado de máquina em Python utilizando a biblioteca scikit-learn para criar um modelo de classificação baseado no algoritmo RandomForestClassifier. O objetivo é prever a espécie de pinguins com base em características como comprimento e profundidade do bico, comprimento da nadadeira, massa do corpo, ilha e sexo.

- Pré-processamento de Dados
  
O conjunto de dados utilizado é o 'penguins' do seaborn, que é carregado e tratado para remover valores nulos. As características numéricas são normalizadas para uma escala padrão, tanto pelo método min/max quanto pela padronização (z-score).

Além disso, as variáveis categóricas 'island' e 'sex' são codificadas usando a técnica de one-hot encoding, criando novas colunas binárias para cada categoria.

- Divisão de Dados
  
Os dados são divididos em conjuntos de treinamento (80%) e teste (20%) usando a função train_test_split do scikit-learn.

- Treinamento do Modelo

Um modelo de classificação RandomForest é criado e treinado com os dados de treinamento usando a função fit do RandomForestClassifier.

- Avaliação do Modelo

O modelo é avaliado usando a acurácia (accuracy_score) e é gerada uma matriz de confusão e um relatório de classificação (precision, recall, F1-score) para fornecer métricas mais detalhadas.

- Fazendo Previsões
  
O modelo treinado é utilizado para fazer previsões em novos dados fornecidos pelo usuário. O usuário é solicitado a inserir informações sobre o novo pinguim, como ilha, profundidade e comprimento do bico, comprimento da nadadeira, massa do corpo e sexo. Esses dados são normalizados e codificados conforme o modelo treinado, e a espécie do novo pinguim é prevista.

- Como Executar

Certifique-se de ter Python instalado em seu ambiente.
Instale as bibliotecas necessárias usando pip install numpy pandas seaborn scikit-learn.
Execute o código fornecido no seu ambiente Python.
Siga as instruções para inserir informações sobre um novo pinguim e veja a previsão do modelo.
Este projeto serve como um exemplo simples de um pipeline de aprendizado de máquina, desde o pré-processamento de dados até a avaliação e previsões em novos dados. Sinta-se à vontade para explorar e ajustar conforme necessário para atender aos seus requisitos específicos.
