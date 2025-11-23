---
title: "Seleção dos Sensores"
date: 2024-04-02T14:30:00Z
draft: false
summary: "Após testes extensivos, escolhemos a nossa suite de sensores: DHT22 para temperatura/humidade e MQ-2 para deteção de fumo."
---

### A Escolha do Hardware
Para detetar incêndios de forma fiável, precisamos de cruzar dados de várias fontes. Não basta apenas a temperatura.

### Componentes Escolhidos
* **Microcontrolador:** ESP32 (Devido ao WiFi e Bluetooth integrados).
* **Temperatura/Humidade:** DHT22 (Mais preciso que o DHT11).
* **Gases/Fumo:** MQ-2 (Sensível a CO e fumo).

Os primeiros testes de bancada mostram resultados promissores na calibração do MQ-2.