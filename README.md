# Introdução a classificação utilizando SKLearn

## Classificação: Porco ou Cachorro?
Na nossa vida aprendemos muitas vezes através da supervisão de outra pessoa, é dessa forma que esse algortmo irá aprender e identificar os dados.

Aqui iremos identificar as seguintes características 1 - sim, 0 - não:
- pelo longo
- perna curta
- faz auau

## Classificação: Acessos em site
Nesse exemplo, entendemos como separar o treino e o test de forma mais fácil, além de inserir uma semente fixa para que a acurácia se matenha constante e estratificar os dados para manter a proporção dos dados.

```train_x, test_x, train_y, test_y = train_test_split(x, y, random_state = seed, test_size = 0.25, stratify = y)```
