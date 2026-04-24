🛡️ SOC Panel LinuxBot Monitoramento
Documentação de Operação e Inteligência de Borda
Este repositório apresenta a interface de gestão e monitoramento de um ecossistema de defesa ativa. O painel foi projetado para centralizar indicadores críticos de segurança e performance, permitindo uma resposta rápida a incidentes em servidores Bare Metal.

🧠 Lógica de Operação (Workflow)
O sistema opera em três camadas distintas, garantindo que a visualização seja independente da execução da defesa:

Camada de Ingestão: O sistema monitora logs de auditoria estruturados, processando eventos de banimento e tentativas de intrusão em tempo real.

Camada de Processamento: Utiliza algoritmos de mineração de dados para categorizar vetores de ataque (ex: Varreduras em diretórios sensíveis, ataques de força bruta em CMS).

Camada de Visualização: Transforma dados brutos em KPIs (Key Performance Indicators) de segurança para tomada de decisão gerencial.

📈 Indicadores de Performance (KPIs) Monitorados
O dashboard foca em métricas de governança que são essenciais para um SOC de elite:

MTTR (Mean Time To Respond): Monitoramento do tempo de reação entre a detecção da ameaça e o bloqueio efetivo na borda.

Eficiência de Borda: Percentual de ataques mitigados na camada de transporte/aplicação antes de atingirem o núcleo do servidor.

Taxa de Ocupação Bare Metal: Correlação entre picos de ataques e consumo de recursos de hardware (CPU/RAM).

📂 Estrutura de Dados Analisada
Para garantir a integridade da análise, o painel processa eventos que contêm:

Identificador do incidente.

Endereço de origem (IP Tracker).

Assinatura do ataque (Classificação de Vetor).
