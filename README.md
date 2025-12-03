<h1 align="center">Projeto MINI GELADEIRA PORTÁTIL IoT PARA TRANSPORTE DE VACINAS</h1>

<p align="center">
  <img src="http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=GREEN&style=for-the-badge"/>
</p>

---

## 🛠 Ferramentas e Tecnologias

<img loading="lazy" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/arduino/arduino-original.svg" width="50" height="50"/><img loading="lazy" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/cplusplus/cplusplus-original.svg" width="50" height="50"/><img loading="lazy" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/git/git-original.svg" width="50" height="50"/><img loading="lazy" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/github/github-original.svg" width="50" height="50"/>

---

## 📌 Descrição do Projeto

A **Mini Geladeira Portátil IoT para Transporte de Vacinas** é um protótipo desenvolvido para manter a temperatura de imunobiológicos dentro da faixa segura de **2°C a 8°C** durante o transporte.  
O sistema utiliza **célula Peltier, sensores internos, IoT e alarmística**, garantindo monitoramento em tempo real, telemetria, rastreabilidade e controle ativo da cadeia de frio.

---

## 🎯 Objetivos Principais

- Desenvolver um sistema IoT capaz de manter vacinas refrigeradas entre **2 e 8 °C**.
- Utilizar **célula Peltier** com controle térmico ativo.
- Registrar e monitorar temperatura, umidade, abertura da tampa e condições gerais.
- Emitir alertas locais e remotos em caso de falhas.
- Garantir **rastreabilidade**, **segurança térmica** e **confiabilidade** no transporte.

---

## 📝 Justificativa

A eficácia das vacinas depende da conservação dentro de uma faixa térmica estreita. Durante transportes móveis podem ocorrer falhas como:

- Ausência de controle ativo (caixas térmicas passivas perdem eficiência).
- Risco de congelamento inesperado.
- Baixa rastreabilidade e monitoramento ineficiente.

Tais problemas podem causar:
- Perda de lotes,
- Custos elevados,
- Riscos à saúde pública.

A solução proposta melhora o controle térmico e fornece monitoramento contínuo via IoT, reduzindo perdas e aumentando a segurança operacional.

---

## 🧪 Metodologia do Projeto

O projeto segue uma abordagem **incremental**, com desenvolvimento e teste de cada subsistema antes da integração completa.

### 🧱 1. Estrutura física e isolamento térmico
Construção da caixa térmica utilizando **EPS/XPS** para minimizar trocas térmicas e melhorar a eficiência da célula Peltier.

### ❄ 2. Sistema de Refrigeração (Célula Peltier)
- Lado frio acoplado a uma *cold plate* metálica.
- Lado quente acoplado a um dissipador com ventoinha.
- Sistema dimensionado para estabilidade e eficiência.

### 🔄 3. Circulação interna de ar
Ventoinha interna para evitar pontos frios e assegurar homogeneidade térmica.

### 🌡 4. Sensoriamento
- Sensor de temperatura do ar interno.  
- Sensor de temperatura no centro da carga (frasco simulado).  
- Sensor de umidade relativa.  
- Sensor magnético (reed switch) para detecção de abertura da tampa.  

### 🔌 5. Controle Eletrônico e IoT
- Microcontrolador **ESP32** para:
  - Leitura dos sensores,
  - Controle PWM da célula Peltier,
  - Alarmes visuais e sonoros,
  - Envio de dados para aplicativo via Bluetooth/Internet.

### 🔋 6. Alimentação e Autonomia
Bateria recarregável de íons de lítio com proteção e autonomia estimada em **4 horas**, permitindo transporte seguro sem energia externa.

### 📱 7. Interface com o Usuário
- LEDs (verde – normal / vermelho – falha),
- Buzzer para alertas críticos,
- Aplicativo móvel exibindo temperatura, umidade, bateria e eventos.

### 🧪 8. Testes e Validação
Serão realizados:
- Teste de estabilização térmica,
- Teste de recuperação após abertura da tampa,
- Teste de autonomia da bateria,
- Teste dos alarmes e telemetria.

---

## :hammer: Funcionalidades

- **Controle ativo da temperatura (célula Peltier + PWM)**  
  Mantém o interior sempre entre **2°C e 8°C**.

- **Monitoramento IoT em tempo real**  
  Dados enviados para aplicativo via Bluetooth ou nuvem.

- **Registro histórico e rastreabilidade**  
  Histórico de temperatura, umidade e eventos.

- **Alarmes locais (LEDs e buzzer)**  
  Ativados quando a temperatura sai da faixa segura.

- **Alerta de abertura da tampa**  
  Via sensor magnético tipo reed switch.

- **Autonomia operacional**  
  Bateria garante operação durante o transporte.

> *Imagens, esquemas elétricos e vídeos serão adicionados futuramente.*

---

## 👨‍🏫 Integrantes do Projeto
- **Beatriz Pimenta**  
- **João Pedro Mendanha**  
- **Júlia Resende**  
- **Kethellen da Silva**  
- **Rafael dos Santos**

---

## 📚 Disciplina
**Internet das Coisas – PUC Minas**  
Professor: **Júlio Conway**

---

## 📅 Data
**31 de Agosto de 2025**

---
