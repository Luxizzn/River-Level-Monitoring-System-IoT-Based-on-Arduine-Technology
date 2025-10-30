#  River Level Monitoring System IoT Based on Arduino Technology


##  Project Description | Descrição do Projeto

**EN:**
The **River Level Monitoring System IoT** is an **environmental monitoring solution** that uses ultrasonic or pressure sensors to measure the **water level in rivers, lakes, or reservoirs**.
The data are processed by an **Arduino board** and automatically sent to an **online platform**, where they can be **stored, analyzed, and displayed in real time**.

This system helps with:

* Flood and overflow prevention
* Environmental and hydrological monitoring
* Applications in agriculture and water resource management
* Academic and research projects in IoT and environmental engineering

**PT:**
O **Sistema IoT de Monitoramento de Nível de Rios** é uma solução de **monitoramento ambiental** que utiliza sensores ultrassônicos ou de pressão para medir o **nível da água em rios, lagos ou reservatórios**.
Os dados são processados por uma **placa Arduino** e enviados automaticamente para uma **plataforma online**, onde podem ser **armazenados, analisados e exibidos em tempo real**.

O sistema auxilia em:

* Prevenção de enchentes e alagamentos
* Monitoramento ambiental e hidrológico
* Aplicações em agricultura e gestão de recursos hídricos
* Projetos acadêmicos de IoT e engenharia ambiental

---

##  Features | Funcionalidades

**EN:**

* 🌊 Real-time measurement of **water level (cm or m)**
* 📡 Automatic data transmission via **Wi-Fi, LoRa, or GSM**
* 💾 **Cloud-based** data storage
* 📈 Historical and graphical data visualization
* ⚠️ **Alert system** for critical water levels
* 🔋 Autonomous operation with **low power consumption**

**PT:**

* 🌊 Medição em tempo real do **nível da água (cm ou m)**
* 📡 Envio automático dos dados via **Wi-Fi, LoRa ou GSM**
* 💾 Armazenamento em **banco de dados na nuvem**
* 📈 Visualização histórica e gráfica das medições
* ⚠️ Sistema de **alerta** para níveis críticos
* 🔋 Operação autônoma com **baixo consumo de energia**

---

##  Technologies Used | Tecnologias Utilizadas

| Category / Categoria                   | Technology / Tecnologia                                                |
| -------------------------------------- | ---------------------------------------------------------------------- |
| **Microcontroller / Microcontrolador** | Arduino UNO / Nano / ESP32                                             |
| **Level Sensor / Sensor de Nível**     | Ultrasonic Sensor (HC-SR04 / JSN-SR04T) or Submersible Pressure Sensor |
| **Communication / Comunicação**        | Wi-Fi (ESP8266 / ESP32), LoRa, or GSM                                  |
| **Cloud / Nuvem**                      | ThingSpeak / Firebase / Node-RED / MQTT Broker                         |
| **Programming Language / Linguagem**   | C/C++ (Arduino IDE)                                                    |
| **Visualization / Visualização**       | Web Dashboard (HTML, CSS, JS or IoT platform)                          |

---

##  System Diagram | Diagrama do Sistema

**EN:**

```
[Level Sensor] ---> [Arduino/ESP32] ---> [Wi-Fi/LoRa] ---> [Cloud Server] ---> [Web Dashboard]
```

**PT:**

```
[Sensor de Nível] ---> [Arduino/ESP32] ---> [Wi-Fi/LoRa] ---> [Servidor/Nuvem] ---> [Dashboard Web]
```

---

##  Project Structure | Estrutura do Projeto

```
River-Level-Monitoring-IoT-Based-on-Arduino/
│
├── /src
│   ├── main.ino                # Main Arduino code / Código principal do Arduino
│   ├── sensors.h               # Sensor reading and calibration / Leitura e calibração do sensor
│   ├── wifi_config.h           # Network setup / Configuração de rede
│
├── /dashboard
│   ├── index.html              # Web interface / Interface web para visualização
│   ├── styles.css              # Dashboard style / Estilo visual
│   └── script.js               # Data update logic / Lógica de atualização dos dados
│
├── /docs
│   ├── diagram.png             # System diagram / Diagrama do sistema
│   ├── circuito.png            # Circuit schematic / Esquema elétrico
│
├── README.md
└── LICENSE
```
