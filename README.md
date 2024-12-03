# **A Dinâmica do Pêndulo**

## **Descrição básica do projeto**

Este projeto é uma simulação criada para ilustrar o comportamento de um pêndulo simples na Física. O objetivo é fornecer uma visualização gráfica do movimento oscilatório, permitindo o estudo e a compreensão dos conceitos envolvidos. A simulação mostra a trajetória de um pêndulo oscilando em diferentes condições, como variações no comprimento da corda e na gravidade.

---

## **Conceitos de Física e Modelo Matemático**

### **Pêndulo Simples**
O pêndulo simples é um sistema mecânico que consiste em uma massa puntiforme, ou seja, um corpo com dimensões insignificantes, presa a um fio de massa desprezível e inextensível capaz de oscilar em torno de uma posição fixa. Graças à sua simplicidade, esse pêndulo é bastante usado durante o estudo do movimento harmônico simples. 

O pêndulo simples é uma aproximação em que não existem forças dissipativas, ou seja, forças de atrito ou de arraste, atuando sobre quaisquer componentes do sistema. Nesses pêndulos, o movimento oscilatório surge em decorrência da ação das forças peso e tração exercida pelo fio.

Como as forças peso e tração não se cancelam nesse contexto, já que isso só acontece na posição de equilíbrio, surge uma força resultante de natureza centrípeta, fazendo o pêndulo oscilar em torno de um ponto de equilíbrio. A partir das equações horárias do movimento harmônico simples e das leis de Newton, é possível determinar um conjunto de equações exclusivas para os pêndulos simples. Para isso, considera-se que a resultante entre a força peso e a força de tração é uma força centrípeta. Além disso, a força restauradora do movimento pendular é a componente horizontal do peso:

![p](https://github.com/user-attachments/assets/64e54e0f-a57e-4ed2-b7f6-108e3bf362b9)

- **Px**: componente horizontal da força peso (N)  
- **Py**: componente vertical da força peso (N)  

A fórmula a seguir é usada para calcular o período no pêndulo simples, relacionando o tempo de uma oscilação completa ao tamanho do fio e à aceleração da gravidade local:

![p](https://github.com/user-attachments/assets/049ae54a-5ccb-426f-9723-2638cd0af775)

**Suposições Adotadas:**
- O fio é **sem massa** e **inextensível**.  
- O sistema está sob uma **força gravitacional uniforme**.  
- Desconsidera-se a resistência do ar.

---

## **Equação do Movimento**

1. A equação geral que rege o movimento do pêndulo:  

![p](https://github.com/user-attachments/assets/e0fe851a-274a-4b1c-84ac-072ec8f04195)

2. Para **pequenos ângulos** (sin(θ) ≈ θ):  

   Esta forma reduzida caracteriza o **movimento harmônico simples**, no qual o pêndulo oscila simetricamente em torno da posição de equilíbrio.

---

## **Relações e Fatores Influentes**

### **Comprimento do Fio (\(L\))**
- O comprimento \(L\) é **inversamente proporcional** à frequência.  
- **Efeitos:**  
  - Aumentar \(L\): **aumento no período (\(T\))**.  
  - Diminuir \(L\): **redução no período (\(T\))**.  
- **Equação do Período:**  
![Period Equation](./equation_3.png)

### **Aceleração Gravitacional (\(g\))**
- A aceleração gravitacional (\(g\)) afeta diretamente a **velocidade da oscilação**.  
- **Efeitos:**  
  - Aumentar \(g\): ciclos **mais rápidos**.  
  - Reduzir \(g\): ciclos **mais lentos**.

### **Amplitude (\(θ₀\))**
- O **ângulo inicial (\(θ₀\))** influencia a altura inicial.  
- **Efeitos:**  
  - Para \(θ₀ < 15°\): Movimento harmônico simples, período constante.  
  - Para \(θ₀ > 15°\): Movimento **não linear**, período aumenta levemente.

### **Massa da Bobina (m)**
- A **massa da bobina não altera o período** ou a frequência do pêndulo (negligenciando a resistência do ar).  
- Isso ocorre porque a força restauradora (gravidade) e a inércia aumentam proporcionalmente com a massa, anulando sua influência.

---

## **Notas sobre Energia**

### **Energia Potencial e Cinética**
- A energia mecânica total do pêndulo é composta por energia potencial gravitacional (\(E_p\)) e energia cinética (\(E_c\)):  
  \[
  E_{total} = E_p + E_c
  \]
- No ponto mais alto (amplitude máxima):  
  - \(E_p\) é máxima, \(E_c = 0\).  
- No ponto mais baixo (posição de equilíbrio):  
  - \(E_c\) é máxima, \(E_p = 0\).

### **Conservação de Energia**
- Em um pêndulo simples ideal (sem dissipação):  
  - A energia mecânica total permanece constante.  
  \[
  E_{total} = m \cdot g \cdot h + \frac{1}{2} m v^2
  \]
- A troca entre \(E_p\) e \(E_c\) descreve o movimento oscilatório.

---

## **Aplicações Práticas**

1. **Medida de Tempo:**  
   - Relógios de pêndulo aproveitam o período constante do pêndulo para cronometragem precisa.

2. **Engenharia:**  
   - Bolas de demolição utilizam princípios semelhantes para maximizar impacto.

3. **Sismologia:**  
   - Pêndulos são usados para detectar e medir movimentos sísmicos.

4. **Experimentos de Física:**  
   - Determinação da aceleração gravitacional local (\(g\)).

---
