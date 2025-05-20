# CP3-IoT 

Este projeto simula um dispositivo ESP32 enviando dados de **temperatura**, **umidade**, **pressão** e **altitude** para um **broker MQTT público (HiveMQ)**.

TECNOLOGIAS: 
  ESP32 (simulado);
  MQTT;
  Broker;

Os dados são enviados para o seguinte tópico:

esp32/sensores
Exemplo de mensagem publicada:
```json
{
  "temperatura": 26.5,
  "umidade": 45.3,
  "pressao": 1012.3,
  "altitude": 87.6
}
```

Link p/ o projeto no Wokwi: https://wokwi.com/projects/431514431010421761

Link do video: https://youtu.be/bTYP9Mhz82c

PS: Estava sem créditos na Azure para poder criar uma VM, mas consegui fazer utilizando MQTT e simulações com o Wokwi.
