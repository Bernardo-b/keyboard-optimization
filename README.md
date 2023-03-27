# Otimização de Teclado

Este é um projeto que utiliza algoritmos genéticos para otimizar a disposição de teclas em um teclado QWERTY para maximizar a velocidade de digitação. A otimização é feita a partir do cálculo de uma pontuação para cada sequência de caracteres, que leva em conta a distância euclidiana entre as coordenadas de cada par de caracteres consecutivos e a frequência de ocorrência de cada par. 

## Base de dados
A base de dados utilizada para treinamento e teste do modelo foi obtida através do Kaggle, disponível no seguinte link: https://www.kaggle.com/datasets/fredericods/ptbr-sentiment-analysis-datasets?resource=download

## Como executar o projeto
Para executar o projeto, é necessário ter o Jupyter Notebook instalado. Em seguida, abra o arquivo `keyboard_optimization.ipynb` e execute todas as células na ordem em que aparecem. Certifique-se de ter as dependências listadas no arquivo `requirements.txt` instaladas em seu ambiente.

## Resultados
Os resultados obtidos pela otimização tendem a agrupar as teclas mais utilizadas no centro do teclado, enquanto as teclas menos utilizadas ficam nas extremidades. Isso permite que a digitação seja mais rápida e eficiente. É possível visualizar o processo de otimização em um gráfico que mostra a evolução da pontuação das gerações ao longo do tempo.

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para criar um pull request ou abrir uma issue para discutir possíveis melhorias ou correções no projeto.

## Licença

Este projeto é licenciado sob a licença MIT. Leia o arquivo `LICENSE` para mais informações.