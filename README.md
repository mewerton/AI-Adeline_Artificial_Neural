# AI-Adeline_Artificial_Neural_Networks_1

Este código implementa um classificador Adaline (Adaptive Linear Neuron) para classificar amostras do conjunto de dados Iris. Ele utiliza uma classe Adaline personalizada que inclui métodos para treinar o modelo (fit), fazer previsões (predict) e calcular a entrada da rede (net_input) e a função de ativação.

O código primeiro carrega o conjunto de dados do Google Drive e o pré-processa, convertendo os rótulos de classe de strings para valores numéricos (-1 para 'Iris-setosa' e 1 para 'Iris-versicolor'). Em seguida, separa as variáveis das amostras e os rótulos de classe, e normaliza as variáveis das amostras usando MinMaxScaler.

O conjunto de dados é dividido em conjuntos de treinamento e teste, com 30% das amostras usadas para teste. O modelo Adaline é treinado no conjunto de treinamento usando o método fit, que ajusta os pesos do modelo com base nas amostras de entrada e nas saídas desejadas. O processo de treinamento visa minimizar o erro quadrático médio (MSE) entre as saídas previstas e as saídas desejadas.

Após o treinamento, o código plota um gráfico mostrando o MSE ao longo das épocas, demonstrando a convergência do processo de treinamento. Em seguida, avalia o desempenho do modelo no conjunto de teste, calculando a acurácia e exibindo o número de erros cometidos durante o teste.

Por fim, o código inclui testes individuais em dois pontos de amostra (A e B) para demonstrar a capacidade do modelo de classificar novas amostras não vistas.

No geral, este código fornece um exemplo claro de como implementar um classificador Adaline em Python usando a biblioteca scikit-learn, e pode servir como uma referência útil para tarefas de classificação semelhantes.

***============================================================***

This code implements an Adaline (Adaptive Linear Neuron) classifier to classify samples from the Iris dataset. It uses a custom Adaline class that includes methods for training the model (fit), making predictions (predict), and calculating the network input (net_input) and activation function.

The code first loads the dataset from Google Drive and preprocesses it, converting the class labels from strings to numerical values (-1 for 'Iris-setosa' and 1 for 'Iris-versicolor'). It then separates the sample variables and class labels, and normalizes the sample variables using MinMaxScaler.

The dataset is split into training and testing sets, with 30% of the samples used for testing. The Adaline model is trained on the training set using the fit method, which adjusts the model weights based on the input samples and desired outputs. The training process aims to minimize the mean squared error (MSE) between the predicted outputs and the desired outputs.

After training, the code plots a graph showing the MSE over epochs, demonstrating the convergence of the training process. It then evaluates the model's performance on the testing set, calculating the accuracy and displaying the number of errors made during testing.

Finally, the code includes individual tests on two sample points (A and B) to demonstrate the model's ability to classify new, unseen samples.

Overall, this code provides a clear example of how to implement an Adaline classifier in Python using the scikit-learn library, and it can serve as a useful reference for similar classification tasks.
