# Pêndulo Simples

Projeto Final de Física I - Simulação Interativa em JavaScript.

## Objetivo do Projeto

Este projeto explora o **pêndulo simples**, um sistema físico que ilustra os conceitos de oscilação, energia mecânica e movimento harmônico simples. A proposta é entender e simular o comportamento do pêndulo com base em suas equações diferenciais.

---

## Fundamentos do Pêndulo Simples

O pêndulo simples é definido como uma massa \(m\) suspensa por um fio de comprimento \(L\), que oscila sob a influência da gravidade \(g\). Suas oscilações podem ser descritas pela seguinte equação diferencial:

\[
\frac{d^2\theta}{dt^2} + \frac{g}{L}\sin(\theta) = 0
\]

### Simplificação para Pequenas Oscilações

Para valores pequenos de \(θ\) (em radianos), podemos aproximar \(\sin(\theta) \approx \theta\), simplificando a equação para:

\[
\frac{d^2\theta}{dt^2} + \frac{g}{L}\theta = 0
\]

Esta é a equação de movimento harmônico simples (MHS), com solução analítica:

\[
\theta(t) = \theta_0 \cos\left(\sqrt{\frac{g}{L}}t\right)
\]

- \(θ(t)\): Deslocamento angular em função do tempo.
- \(\theta_0\): Ângulo inicial (em radianos).
- \(T = 2\pi \sqrt{\frac{L}{g}}\): Período do pêndulo.

---

## Equações Relacionadas

1. **Velocidade Angular (\(\omega\)):**

   \[
   \omega(t) = -\theta_0 \sqrt{\frac{g}{L}} \sin\left(\sqrt{\frac{g}{L}}t\right)
   \]

2. **Aceleração Angular (\(\alpha\)):**

   \[
   \alpha(t) = -\frac{g}{L} \theta(t)
   \]

3. **Energia Mecânica:**

   - Energia cinética (\(E_k\)): \( \frac{1}{2}mv^2 \)
   - Energia potencial (\(E_p\)): \( mgh \)

   A energia total (\(E_t\)) do sistema é conservada:
   \[
   E_t = E_k + E_p
   \]

---

## Aplicações Reais

- **Relógios de Pêndulo:** O princípio do movimento harmônico simples é usado para medir tempo com precisão.
- **Determinação da Gravidade (\(g\)):** Experimentos com pêndulos podem calcular o valor de \(g\) localmente.
- **Educação Física:** É um exemplo clássico de movimento periódico.

---

## Estrutura do Projeto

O projeto está estruturado em uma simulação interativa onde você pode ajustar os seguintes parâmetros:

1. **Comprimento do Fio (\(L\)):** Controla o período \(T\) do pêndulo.
2. **Gravidade (\(g\)):** Simula diferentes campos gravitacionais.
3. **Ângulo Inicial (\(θ₀\)):** Determina a amplitude da oscilação.

A interface permite visualizar, em tempo real, como as oscilações se comportam quando esses valores são alterados.

---

## Como Executar

1. Clone o repositório para sua máquina:
   ```bash
   git clone https://github.com/seu-usuario/pendulo-simples.git
