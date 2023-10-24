# Método de Widrow-Hoff

O método de Widrow-Hoff, também conhecido como **Regra Delta** ou **Algoritmo LMS (Least Mean Square)**, é uma técnica utilizada para treinar redes neurais simples, focando em minimizar o erro entre as saídas desejadas e as saídas reais de um neurônio.

## Como Funciona?

A cada iteração de treinamento, os pesos da rede são ajustados com base na diferença (erro) entre a saída esperada e a saída atual do neurônio.

### Fórmula de atualização

A atualização dos pesos é feita utilizando a seguinte fórmula:

$$ w_{\text{new}} = w_{\text{old}} + \eta \times e \times x $$

Onde:

\( w_{\text{new}} \) e \( w_{\text{old}} \) são os pesos novo e antigo, respectivamente.
\( \eta \) é a taxa de aprendizado.
\( e \) é o erro, calculado como \( e = d - y \), onde \( d \) é a saída desejada e \( y \) é a saída atual do neurônio.
\( x \) é a entrada para o neurônio.

## Por que é Importante?

O algoritmo de Widrow-Hoff é um dos primeiros e mais fundamentais métodos de treinamento de redes neurais. Ele serve como base para muitos outros algoritmos mais sofisticados usados no campo do aprendizado de máquina.
