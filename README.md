<div align="center">
  <kbd>
    <h1 style="color: #00ff41;">🛡️ SOC PANEL LINUXBOT MONITORAMENTO</h1>
  </kbd>
  <p><strong>Documentação de Operação e Inteligência de Borda</strong></p>
</div>

<hr style="border: 0.5px solid #00ff41;">

<blockquote style="background-color: #0a0a0a; border-left: 5px solid #00ff41; padding: 15px; color: #00ff41; font-family: 'Courier New', Courier, monospace;">
  <strong>[STATUS: OPERACIONAL]</strong><br>
  Este repositório apresenta a interface de gestão e monitoramento de um ecossistema de defesa ativa. O painel foi projetado para centralizar indicadores críticos de segurança e performance, permitindo uma resposta rápida a incidentes em servidores Bare Metal.
</blockquote>

## 🧠 Lógica de Operação (Workflow)
O sistema opera em **três camadas distintas**, garantindo que a visualização seja independente da execução da defesa:

* **⚡ Camada de Ingestão:** Monitoramento de logs de auditoria estruturados, processando eventos de banimento e tentativas de intrusão em tempo real.
* **⚙️ Camada de Processamento:** Algoritmos de mineração de dados para categorizar vetores de ataque (ex: Varreduras em diretórios sensíveis, ataques de força bruta em CMS).
* **🖥️ Camada de Visualização:** Transformação de dados brutos em KPIs de segurança para tomada de decisão gerencial.

## 📈 Indicadores de Performance (KPIs) Monitorados
O dashboard foca em métricas de governança que são essenciais para um SOC de elite:

1.  **MTTR (Mean Time To Respond):** Tempo de reação entre a detecção da ameaça e o bloqueio efetivo na borda.
2.  **Eficiência de Borda:** Percentual de ataques mitigados antes de atingirem o núcleo do servidor.
3.  **Taxa de Ocupação Bare Metal:** Correlação entre picos de ataques e consumo de recursos de hardware (CPU/RAM).

## 📂 Estrutura de Dados Analisada
O painel processa eventos contendo as seguintes metadados:
* `Identificador do incidente`
* `Endereço de origem (IP Tracker)`
* `Assinatura do ataque (Classificação de Vetor)`

<hr style="border: 0.5px solid #00ff41;">

<div align="right">
  <sub>V18 Adaptive Edge SOC | Desenvolvido por DicCarlo</sub>
</div>
