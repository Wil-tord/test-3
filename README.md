# **A Dinâmica do Pêndulo**

## **Descrição Básica do Projeto**

Este projeto é uma simulação gráfica criada para ilustrar o comportamento de um pêndulo simples na Física. O objetivo principal é explorar visualmente o movimento oscilatório, permitindo estudar conceitos como variações no comprimento da corda e na gravidade.

---

## **Conceitos de Física e Modelo Matemático**

### **Pêndulo Simples**

Um pêndulo simples é um sistema mecânico composto por uma massa puntiforme presa a um fio inextensível e de massa desprezível. Ele oscila sob a influência das forças peso e tração, criando um movimento harmônico simples (MHS) em condições ideais. Para este modelo, consideramos:

- **Sem forças dissipativas** (como atrito ou resistência do ar).  
- **Sistema idealizado** com movimento oscilatório uniforme.  

A força restauradora responsável pelo movimento é a componente horizontal do peso, enquanto a componente vertical é equilibrada pela tração do fio.

### **Equação do Período (T)**

Para um pêndulo simples, o período \(T\) é dado por:

\[
T = 2\pi \sqrt{\frac{L}{g}}
\]

Onde:  
- \(T\): Período do ciclo (s).  
- \(L\): Comprimento do fio (m).  
- \(g\): Aceleração gravitacional local (\(m/s^2\)).

---

## **Equação do Movimento**

1. **Equação Geral do Movimento**  

\[
\theta'' + \frac{g}{L} \sin(\theta) = 0
\]

2. **Aproximação para Pequenos Ângulos (\( \sin(\theta) \approx \theta\)):**

\[
\theta'' + \frac{g}{L} \theta = 0
\]

Esta simplificação caracteriza o **movimento harmônico simples (MHS)**, permitindo análises mais acessíveis em situações práticas.

---

## **Relações e Efeitos**

### **1. Comprimento do Fio (\(L\))**

- Relação: **\(T \propto \sqrt{L}\)**  
- **Efeitos:**  
  - Aumentar \(L\): período mais longo.  
  - Diminuir \(L\): período mais curto.

### **2. Aceleração Gravitacional (\(g\))**

- Relação: **\(T \propto 1/\sqrt{g}\)**  
- **Efeitos:**  
  - Aumentar \(g\): ciclos mais rápidos.  
  - Diminuir \(g\): ciclos mais lentos.

### **3. Amplitude (\(θ₀\))**

- Pequenos ângulos (\(<15°\)): movimento harmônico.  
- Grandes ângulos (\(>15°\)): movimento não linear, com aumento perceptível no período.

### **4. Massa da Bobina (\(m\))**

A massa não afeta o período, pois o movimento do pêndulo depende apenas de \(L\) e \(g\), considerando forças dissipativas desprezíveis.

---

## **Aplicações Práticas**

### **1. Medida de Tempo**
Relógios de pêndulo utilizam o período constante do pêndulo para cronometragem precisa.

### **2. Engenharia**
Bolas de demolição seguem princípios semelhantes para maximizar impacto em alvos específicos.

### **3. Sismologia**
Pêndulos ajudam na detecção e medição de movimentos sísmicos.

### **4. Experimentos de Física**
Determinação da aceleração gravitacional local (\(g\)) com alta precisão.

---

## **Conclusão**

Este projeto demonstra a utilidade de um modelo matemático simples para compreender fenômenos complexos. A simulação interativa oferece uma forma prática de explorar conceitos teóricos e aplicá-los em contextos reais, unindo aprendizado teórico e visualização dinâmica.

---

## **Imagens Referenciadas**

### Componente Horizontal e Vertical do Peso

![Componente Horizontal e Vertical do Peso](https://github.com/user-attachments/assets/64e54e0f-a57e-4ed2-b7f6-108e3bf362b9)

### Equação do Período no Pêndulo Simples

![Equação do Período](https://github.com/user-attachments/assets/049ae
