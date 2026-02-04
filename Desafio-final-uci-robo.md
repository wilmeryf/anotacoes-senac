# 🤖 Desafio Final — UCI | Montagem e Ligação de Robô com Arduino

> Documentação do desafio final de UCI envolvendo montagem elétrica,
> uso de Arduino, CI L293D, motores e sensores.
> Conteúdo baseado em aula prática.

---

## 🎯 Objetivo do Projeto

Realizar a montagem elétrica e lógica de um robô utilizando:
- Arduino
- Ponte H (CI L293D)
- Motores DC
- Sensor sonar
- Alimentação por bateria

---

## 🔌 Alimentação e Energia

### Observação importante
- O Arduino funciona com tensão entre **7V e 12V**
- Tensão ideal utilizada: **9V**

---

## ⚙️ Etapas de Ligação do Robô

### 🔴 Parte 1 — Alimentação positiva
- Ligar um **fio vermelho** no polo positivo da bateria
- Conectar esse fio ao **interruptor**
- Utilizar o lado **não comum** do interruptor

---

### 🔁 Parte 2 — Saída do interruptor
- Ligar o **pino comum do interruptor**
- Conectar à **ponte H (lado direito inferior)**
- Região sem marcação específica para motores

---

### ⚫ Parte 3 — Negativo (GND)
- Ligar os **dois pinos centrais** no negativo
- Realizar a ligação:
  - Placa inferior
  - Placa superior
- Criar um **rabicho** para distribuição do **GND**

---

### ⚡ Parte 4 — Alimentação do Arduino
- Conectar o pino **VIN** do Arduino
- Alimentar com **9V**
- A ligação vem do **pino comum do interruptor**

---

### ⚫ Parte 5 — GND Arduino → CI
- Ligar um **fio preto**
- Do **GND do Arduino**
- Para o **CI L293D**

---

### 🔋 Parte 6 — 5V Arduino → CI
- Ligar o **5V do Arduino** ao CI
- Fazer um **jumper** na parte superior do CI

---

### 🔁 Parte 7 — Jumper de 5V para motores
- Criar mais um **jumper**
- Do pino **5V**
- Para o pino responsável pelos motores no CI

---

### 📡 Parte 8 — Ligação do Sonar
- Conectar o **VCC do sonar** ao **5V do CI**
- Conectar o **GND do sonar** diretamente ao **Arduino**

---

## 🔄 Ligação dos Motores

### 🟢 Motor 1
- Conectar nos pinos **3 e 6** do CI (saídas)
- Utilizar fios de cor verde

#### Controle (inputs):
- Inputs do CI: **2 e 7**
- Ligar aos pinos **PWM 5 e 6** do Arduino
- Conexão feita na parte inferior do CI

---

### 🟢 Motor 2
- Conectar nos pinos **14 e 11** do CI
- Controle pelo Arduino:
  - Pinos **9 e 10** do Arduino
  - Ligados às portas **15 e 10** do CI

---

## 🎛️ Controle PWM

### O que é PWM?
- PWM = *Pulse Width Modulation*
- Usado para **controlar velocidade dos motores**

### Características:
- PWM vai de **0 a 255**
- Utiliza o comando:
```cpp
analogWrite(pino, valor);
```

- Apesar do nome, não é analógico

- O sinal apenas liga e desliga rapidamente

- Funciona apenas em pinos digitais com o símbolo ```~```

### Pinos PWM utilizados no projeto:
```
~3, ~5, 9, 10, 11
```

---

## ✂️ Ajustes Físicos

- Cortar fios para criar jumpers

- Organização dos jumpers diretamente no CI L293D

- Garantir bom contato para evitar falhas

---

## 📦 Lista de Componentes

- Arduino

- CI L293D (Ponte H)

- Motores DC

- Sensor sonar

- Bateria (9V)

- Interruptor

- Jumpers

- Fios

- Protoboard
