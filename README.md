# 🛡️ SIMULADOR DE SOC 

## 🎯 Visão Geral  
  
#### 📑 SOBRE O PROJETO  
Este repositório é dedicado à documentação técnica e prática dos meus treinamentos na plataforma HACKONE, focado na formação de Analista de SOC (Security Operations Center). Aqui, aplico os conhecimentos teóricos da minha graduação em Cibersegurança para resolver cenários reais de ameaças em infraestruturas complexas.  
#### 🕵 OBJETIVO DO TREINAMENTO  
Capacitação técnica no ciclo de vida de incidentes de segurança, desde a detecção inicial através de SIEM/XDR até a contenção e erradicação de ameaças, seguindo os frameworks NIST e MITRE ATT&CK.

#### 🛠️ COMPETÊNCIAS DESENVOLVIDAS  
Monitoramento de Eventos: Gestão de dashboards críticos e análise de métricas de risco.  
  
Triagem de Alertas: Identificação e priorização de incidentes baseados em severidade e impacto ao negócio.   
    
Análise de Logs: Investigação profunda de logs de firewalls e sistemas operacionais para identificação de IOCs (Indicadores de Comprometimento).
  
Threat Intelligence: Utilização de bases de vulnerabilidades (CVEs) para correlacionar ameaças externas com o ambiente interno.
 

#### 🏗️ ARQUITETURA DO AMBIENTE MONITORADO  
Para a execução destes laboratórios, o ambiente simulado é composto por uma infraestrutura robusta que permite a prática de defesa em profundidade:

Perímetro: 5 Firewalls da Fortinet protegendo diferentes sites da organização.

Endpoints: Servidores Linux e Windows configurados para envio de telemetria em tempo real.

Visibilidade: Fluxo de dados centralizado via túneis VPN IPsec para a plataforma de análise Securityone.    

  
                                                     DASHBOARD DO SIEM  

![](SIEM.hackone.png)  


---  
## Laboratório 1 - Reconhecimento de Ameaça, Severidade e Impacto

### 📌 Objetivo do laboratório  
Identificar o incidente #81  Responder as seguintes perguntas:  

---  
> Qual é o nível de severidade desse incidente?    
> Qual o Tipo de ameaça desse incidente?  
> Qual é o impacto que esse incidente representa?  
> O que é o serviço de SSH citado?   
---
![](%2381%20Brute%20Force%20SIEM%20p1.png)
![](%2381%20Brute%20Force%20SIEM%20p2.png)

### 🚨 Diagnóstico  
---

> A severidade apresentada é Alta.  
> A ameaça no inicidente 81 é um ataque de brute force no SSH.  
> Apresenta múltiplos riscos que vão desde exposição de dados sensíveis, Indisponibilidade (DoS),Movimentação Lateral ou mesmo Comprometimento de Credenciais.  
> O SSH (Secure Shell) é um protocolo de rede que permite a comunicação e a administração remota de sistemas de forma criptografada.
---





