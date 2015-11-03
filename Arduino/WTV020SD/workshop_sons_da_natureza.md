---
layout: protomake
title: Arduino + WTV020SD
---

## Conceitos

*   Conversão Analógico-Digital
  *   [PWM](http://www.embarcados.com.br/arduino-saidas-pwm/)
*   Eletrônica Básica
*   Open Source / Comunidade

## Materiais
*   Arduino UNO
*   WTV020SD
*   Alto-Faltantes
*   Protoboard (para facilitar a prototipagem)
*   Botões de simples acionamento (para controle do módulo)
*   Resistores
*   LEDs (para indicação de funcionamento)
*   Cartão Micro SD 2Gb
*   Software Hotkeys for Arduino

## Características WTV020SD

1. Funciona com cartão de memória Micro SD;
2. Frequência de trabalho para AD4: 6KHz a 32KHz;
3. Frequência de trabalho para WAV: 6KHz a 16KHz;
4. Placa Conversora Digital-Analógica 16bits e saída de audio PWM;
6. Aceita controle por micro-processador e controle por teclas;
7. Funciona SEM micro-processador
8. Voltagem operacional: DC2.5 ~ 3.6V;

## Passos
### Montar circuito básico e instalar bibliotecas (30 min)
![Alt text](/Arduino/WTV020SD/_pics/diagrama_sem_arduino "Montagem Básica")  
"Esquemático para Montagem Básica (Fonte: BuildCircuit)"  

![Alt text](/Arduino/WTV020SD/_pics/diagrama_led.png "Diagrama LED")  
"Diagrama de funcionamento do LED (Fonte: thalesnicoleti)"  

### Baixar [Samples](https://mega.nz/#!4RN3VRbC!nu8mjApjJ-MkKKPq9EVwQ2TfoTf3nNRNpzcQeEM9-50) e Testar! (10 min)

### Converter .MP3 para .AD4 (30 min)
1. Baixar e abrir [USB Recorder](https://mega.nz/#!sU0SxaKQ!_0WuBYE-fSiBwaLse282Z6pYjxTPzv1BDCKLX5xNHKc)
2. Ajustar sample rate para 32000
3. Selecionar as músicas e clicar "Encode"
4. Renomear de 0000 até 0512
Se der problema, ajustar volume (<6dB) pelo Audacity

### Modificar circuito e subir código (30 min)
![Alt text](/Arduino/WTV020SD/_pics/montagem_arduino.jpg "Montagem com Arduino")  
"Esquemático para Montagem com Arduino (Fonte: BuildCircuit)"  

1. Baixar e Instalar Arduino
2. Baixar Biblioteca WTV020SD para Arduino  
~~http://forum.arduino.cc/index.php?action=dlattach;topic=117009.0;attach=34018~~  
3. Compilar Exemplo

### Instalar Hotkeys for Arduino (20 min)
### Explorar! (30 min)

## Referências

*   [BuildCircuit](http://www.buildcircuit.com/how-to-use-wtv020sd-music-module-with-arduino/)
*   [WTV020SD Manual](http://letsmakerobots.com/files/WTV020_manual_V1.3.pdf)
*   [Forum Arduino](http://forum.arduino.cc/index.php?topic=117009.0)
*   [Arduino Eletrônica](http://www.arduinoeletronica.com.br/2014/08/converter-arquivos-mp3-para-ad4player.html#.Vikc-TRXTXg)
*   [Makezine](http://makezine.com/projects/instant-nature-quick-peaceful/)
