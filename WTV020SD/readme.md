---
layout: workshop
title: Arduino + WTV020SD
---

## Conceitos

*   Conversão Analógico-Digital
  *   [PWM](http://www.embarcados.com.br/arduino-saidas-pwm/)
*   Eletrônica Básica
*   Open Source / Comunidade

## Materiais
*   WTV020SD
*   Alto-Faltantes
*   Protoboard 170 pinos
*   Botões de simples acionamento
*   Resistore 470R
*   LED (para indicação de funcionamento)
*   Regulador de Tensão LM1117T
*   Cartão Micro SD

## Características WTV020SD

1. Funciona com cartão de memória Micro SD;
2. Frequência de trabalho para AD4: 6KHz a 32KHz;
3. Frequência de trabalho para WAV: 6KHz a 16KHz;
4. Placa Conversora Digital-Analógica 16bits e saída de audio PWM;
6. Aceita controle por micro-processador e controle por teclas;
7. Funciona SEM micro-processador
8. Voltagem operacional: DC2.5 ~ 3.6V;

## Passos
### 1. Montar circuito básico e instalar bibliotecas (30 min)
![Alt text](/WTV020SD/_pics/diagrama_sem_arduino.png "Montagem Básica")  
"Esquemático para Montagem Básica (Fonte: BuildCircuit)"  

![Alt text](/WTV020SD/_pics/diagrama_led.png "Diagrama LED")  
"Diagrama de funcionamento do LED (Fonte: thalesnicoleti)"  

### 2. Preparar cabo USB para fonte de alimentação
![Alt text](/WTV020SD/_pics/usb_cable.jpg "Preparação Cabo USB")  
"Hack That Holy USB! (Fonte: instructables)"

### 3. Soldar alto-falantes

### 4. Baixar [Formatter 3](https://www.sdcard.org/downloads/formatter_3/) e Formatar Cartão Micro SD (10 min)
Selecionar opção "Overwrite Format".

### 5. Baixar [Samples](https://mega.nz/#!4RN3VRbC!nu8mjApjJ-MkKKPq9EVwQ2TfoTf3nNRNpzcQeEM9-50) e Testar! (10 min)

### 6. Baixar sons
http://www.freesfx.co.uk/soundeffects/
http://soundbible.com/ 
http://www.orangefreesounds.com/  

### 7. Converter .MP3 para .AD4 (30 min)
1. Baixar e abrir [USB Recorder](https://mega.nz/#!sU0SxaKQ!_0WuBYE-fSiBwaLse282Z6pYjxTPzv1BDCKLX5xNHKc)
2. Ajustar sample rate para 32000
3. Localizar pasta, selecionar as músicas e clicar "Encode"
4. Renomear de 0000 até 0512
Se der problema, ajustar volume (<6dB) pelo Audacity  

### 8. Maestro: música!!!

## Referências

*   [BuildCircuit](http://www.buildcircuit.com/how-to-use-wtv020sd-music-module-with-arduino/)
*   [WTV020SD Manual](http://letsmakerobots.com/files/WTV020_manual_V1.3.pdf)
*   [Forum Arduino](http://forum.arduino.cc/index.php?topic=117009.0)
*   [Arduino Eletrônica](http://www.arduinoeletronica.com.br/2014/08/converter-arquivos-mp3-para-ad4player.html#.Vikc-TRXTXg)
*   [Makezine](http://makezine.com/projects/instant-nature-quick-peaceful/)
*   [Hack That Holy USB Cable](http://www.instructables.com/id/Hack-that-holy-USB-cable/)


## Contatos
hello@wefab.cc  
rafael@wefab.cc
