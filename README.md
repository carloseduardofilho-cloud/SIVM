# SIVM
Sistema de Identificação de Vibração em Máquinas (SIVM).

# Projeto SIVM
O produto consiste em um sistema inteligente e compacto de monitoramento de vibração, projetado para a manutenção preditiva de equipamentos industriais. Essencialmente, um sensor acelerômetro acoplado à máquina captura dados vibracionais em tempo real, que são imediatamente processados por um microcontrolador ESP32. Este dispositivo executa um algoritmo que analisa métricas cruciais como a intensidade da vibração (RMS) e as frequências dominantes (via FFT) para diagnosticar anomalias e identificar falhas iminentes, como desalinhamento ou desgaste. Ao detectar um padrão fora do normal, o sistema emite um alerta visual local por meio de um LED e envia os dados via Wi-Fi para um dashboard ou terminal.
