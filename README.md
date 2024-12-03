# Pêndulo Simples

Projeto final de Física I: Uma introdução ao comportamento oscilatório de um pêndulo simples, com explicações claras e organizadas.

---

## **Introdução**

O pêndulo simples é uma ferramenta clássica na física para estudar oscilações. Ele consiste em um corpo suspenso por um fio que, ao ser deslocado de sua posição de equilíbrio, realiza movimentos oscilatórios devido à força gravitacional.

![Pêndulo Simples - Placeholder](assets/pendulum.png)

---

## **Equações Fundamentais**

As equações que regem o movimento do pêndulo são:

### 1. **Equação Geral**

O movimento do pêndulo pode ser descrito pela seguinte equação diferencial de segunda ordem:

![Equação Geral](assets/equation_1.png)

Essa equação descreve o movimento do pêndulo em função do ângulo de deslocamento (\(θ\)) e da aceleração gravitacional (\(g\)).

### 2. **Aproximação para Pequenos Ângulos**

Quando o ângulo de oscilação é pequeno (\(θ \ll 1\)), podemos aproximar o seno do ângulo por sua própria medida (ou seja, \( \sin(\theta) \approx \theta \)). Com isso, a equação do movimento se simplifica para:

![Equação Simplificada](assets/equation_2.png)

Este é o modelo de **Movimento Harmônico Simples (MHS)**, o qual é muito mais fácil de resolver e fornece resultados mais próximos das oscilações reais para pequenos ângulos.

### 3. **Período de Oscilação**

A equação do período \(T\) para o pêndulo em MHS é dada por:

![Equação do Período](assets/equation_3.png)

Onde:
- \(L\) é o comprimento do fio que suspende o pêndulo.
- \(g\) é a aceleração gravitacional local.
- O período \(T\) é o tempo necessário para uma oscilação completa.

Essa equação nos diz que o período \(T\) não depende da massa do pêndulo, mas sim do comprimento do fio e da gravidade local.

---

## **Parâmetros Importantes**

### Comprimento (\(L\)):
- **Descrição:** O comprimento do fio que sustenta o pêndulo.
- **Efeito:** O aumento de \(L\) faz com que o período (\(T\)) aumente, resultando em um movimento mais lento.
- **Relação:** A relação \(T = 2\pi\sqrt{\frac{L}{g}}\) mostra como o período é sensível ao comprimento do fio.

### Gravidade (\(g\)):
- **Descrição:** A aceleração gravitacional no local onde o pêndulo está sendo estudado. 
- **Efeito:** A gravidade maior acelera o movimento do pêndulo, reduzindo o seu período.
- **Observação:** Em altitudes maiores ou em outros planetas, o valor de \(g\) pode variar, afetando o período da oscilação.

### Ângulo Inicial (\(θ₀\)):
- **Descrição:** O ângulo com o qual o pêndulo é deslocado da posição de equilíbrio.
- **Efeito:** Para pequenos valores de \(θ₀\), o movimento permanece harmônico (período constante). Para grandes valores, o movimento se torna não-linear e o período aumenta.

---

## **Comportamentos Interessantes**

### Oscilações Pequenas (\(θ₀ ≈ 0\)):
Quando o ângulo inicial \(θ₀\) é pequeno, o movimento pode ser aproximado como harmônico simples, ou seja, a força restauradora é diretamente proporcional ao deslocamento (\(F = -k \cdot x\)).

- **Período constante:** O movimento é periódico, e o período não depende da amplitude de oscilação. A fórmula \(T = 2\pi\sqrt{\frac{L}{g}}\) descreve esse comportamento.

### Oscilações Grandes:
Quando o ângulo \(θ₀\) aumenta (geralmente mais de 15°), o movimento deixa de ser harmônico simples e se torna não-linear. A força restauradora não segue mais uma relação linear com o deslocamento.

- **Variação do Período:** O período aumenta ligeiramente com o aumento da amplitude (\(θ₀\)).

---

## **Aplicações Práticas**

1. **Relógios de Pêndulo:** 
   - Utilizam o movimento regular para medir o tempo com precisão. O relógio de pêndulo foi um dos primeiros instrumentos de medição do tempo de alta precisão.

2. **Sismologia:**
   - Dispositivos pendulares são usados para detectar e medir movimentos sísmicos. O princípio do pêndulo simples é útil para entender os tremores da Terra.

3. **Educação:**
   - Experimentos simples com pêndulos são frequentemente usados para ensinar conceitos de física como aceleração gravitacional, movimento harmônico e períodos de oscilação.

---

## **Experimentos Recomendados**

1. **Medir o Período \(T\):**
   - Meça o tempo de 10 oscilações e calcule \(T\).
   - Varie \(L\) e compare os resultados experimentais com a fórmula teórica \(T = 2\pi\sqrt{\frac{L}{g}}\).

2. **Estudo do Ângulo Inicial (\(θ₀\)):**
   - Experimente diferentes valores de \(θ₀\) e observe a mudança no período de oscilação.

3. **Gravidade (\(g\)):**
   - Realize experimentos em diferentes altitudes ou com diferentes valores de \(g\), como em planetas fictícios ou na Lua.

---

## **Referências e Links Úteis**

- [Documentação de Física I (Adicionar link)](#)
- [Simulações Interativas (Adicionar link)](#)
- [Artigo Científico sobre Pêndulos (Adicionar link)](#)

---

## **Créditos**

- Este material foi desenvolvido como parte do Projeto Final de Física I.
- Autor: _[Seu Nome]_.
- Imagens e gráficos gerados ou adaptados a partir de fontes abertas.

---

## **Licença**

Este projeto está licenciado sob a [MIT License](LICENSE).
