# Aquacontrol

# 💧 AquaControl — Sistema Inteligente de Irrigação

O AquaControl é um projeto de irrigação automatizada que busca otimizar o uso da água por meio de controle remoto, monitoramento e automação. O sistema utiliza um ESP32 para controlar o acionamento de uma válvula e uma interface web para facilitar o gerenciamento da irrigação.

Atualmente, o projeto está em fase de prototipagem e simulação, utilizando o Wokwi para testar o circuito e desenvolver suas funcionalidades.

🎯 Objetivos

- Automatizar o acionamento de uma válvula de irrigação.
- Permitir o controle remoto por meio de uma interface web.
- Monitorar a umidade do solo e o consumo de água.
- Implementar a irrigação automática com base nos dados dos sensores.
- Promover o uso mais eficiente da água.

⚙️ Tecnologias utilizadas

- C++ — programação do ESP32.
- HTML, CSS e JavaScript — desenvolvimento da interface web.
- MQTT — comunicação entre a interface e o dispositivo.
- HiveMQ — broker MQTT utilizado nos testes.
- Wokwi — simulação do circuito eletrônico.

🚀 Como funciona

1. O ESP32 conecta-se à rede Wi-Fi e ao broker MQTT.
2. A interface web envia comandos para abrir ou fechar a válvula.
3. O ESP32 recebe os comandos e atualiza o estado simulado do sistema.
4. LEDs representam visualmente os estados de válvula aberta e fechada.
5. A interface recebe atualizações por meio do MQTT.
6. Futuramente, uma tela TFT LCD e sensores permitirão acompanhar informações adicionais da irrigação.

🛠️ Funcionalidades

- [x] Controle simulado de abertura e fechamento da válvula.
- [x] Comunicação entre ESP32 e interface web via MQTT.
- [x] Representação do estado da válvula por LEDs.
- [ ] Integração de uma tela TFT LCD.
- [ ] Leitura de um sensor de umidade do solo.
- [ ] Medição do fluxo e consumo real de água.
- [ ] Irrigação automática conforme a umidade do solo.
- [ ] Histórico de funcionamento e consumo.
- [ ] Mecanismos de segurança para falhas de conexão.

🧪 Simulação

O protótipo é desenvolvido no [Wokwi](https://wokwi.com/), permitindo testar o comportamento do sistema antes da montagem física.

A comunicação MQTT utiliza o broker público HiveMQ. Essa configuração é destinada a testes e demonstrações; uma instalação real precisará de autenticação, controle de acesso e medidas adicionais de segurança.

📌 Estado do projeto

O AquaControl está em desenvolvimento. O controle da válvula é representado por LEDs na simulação. A integração com sensores físicos, a medição real do consumo de água e a instalação de uma válvula hidráulica estão previstas para etapas futuras.

🌱 Contribuições

Sugestões, melhorias e contribuições são bem-vindas. O objetivo é desenvolver uma solução acessível de automação para irrigação, priorizando a eficiência hídrica e a simplicidade de uso.

---

AquaControl — tecnologia a serviço do uso consciente da água.
