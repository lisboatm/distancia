# Problema dos Carros (X e Y)

## Descrição

Este programa calcula o tempo necessário para o carro Y se distanciar do carro X, dado que ambos partem da mesma posição, mas com velocidades diferentes. O carro X tem uma velocidade constante de 60 km/h, enquanto o carro Y viaja a 90 km/h. A diferença de velocidade entre os dois carros resulta em um aumento constante da distância entre eles.

## Objetivo

Leia a distância em quilômetros que o carro Y precisa alcançar em relação ao carro X e calcule quanto tempo (em minutos) levará para que isso ocorra.

## Entrada

O arquivo de entrada contém um único número inteiro que representa a distância (em Km) que o carro Y deseja tomar em relação ao carro X.

- **Formato:** `d`
- **Restrições:** \( d \geq 1 \)

## Saída

A saída deve apresentar o tempo necessário para que o carro Y se distancie do carro X, seguido da palavra "minutos".

- **Formato:** `tempo minutos`

## Cálculo

A diferença de velocidade entre os carros é:

\[ \text{Diferença de Velocidade} = V_{Y} - V_{X} = 90 \, \text{km/h} - 60 \, \text{km/h} = 30 \, \text{km/h} \]

A cada hora, o carro Y se afasta do carro X em 30 km. Portanto, para encontrar o tempo necessário (em minutos) para o carro Y tomar uma distância \( d \):

1. Calcule o tempo em horas:

\[ \text{tempo\_horas} = \frac{d}{30} \]

2. Converta o tempo para minutos:

\[ \text{tempo\_minutos} = \text{tempo\_horas} \times 60 \]

## Exemplo

### Entrada

```
60
```

### Saída

```
120 minutos
```

### Explicação

Neste exemplo, se o carro Y precisa se distanciar 60 km do carro X, levará 120 minutos para alcançar essa distância.

## Implementação

Para implementar esse problema, você pode usar qualquer linguagem de programação que suporte operações básicas de entrada e saída. O algoritmo deve ser eficiente, considerando que a entrada é um único inteiro.

## Considerações Finais

Certifique-se de testar o programa com diferentes valores de entrada para garantir que ele funcione corretamente em todos os casos possíveis. Lembre-se de que a entrada deve sempre ser um número inteiro positivo.
