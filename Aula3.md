## Descrever as funcionalidades das soluções de segurança da Microsoft

### Modelo OSI 
![image](https://github.com/mariannaariel/SecurityGirls/assets/49196442/28da65f9-ba95-47a5-bd19-2d7bbb57b510)

NGS - grupo de segurança de rede do azure - filtros de comunicação entre redes virtuais ou vnets, bloquear entrada da internet
entrada | saída 
![image](https://github.com/mariannaariel/SecurityGirls/assets/49196442/eb2762df-8207-41bb-8eb0-2a5926a32b10)

Filtrar tráfego na camada de rede (camada 3 camada 4)

Firewall do Azure
Regra de acesso, Microsoft Threat Intelligence(ips dominios que ja são conhecidos por ter atividade suspeita) | nativo de nuvem

![image](https://github.com/mariannaariel/SecurityGirls/assets/49196442/893c2042-54f8-401c-ba74-fa82ae555c79)
Sistema de previsão e detecção de intrusão
camada 3,4 e 7

Firewall do aplicativo web 
camada 7 proteção a bots 

Proteção contra DDoS do Azure 
Standard x Nativa = Nivelamento de quantidade de acessos, alertas e monitoração em tempo real 

Azure Bastion serviço PaaS
Acessar máquina virtual sem necessitar de ip público 
protocolo RDP/SSH porém com ip privado 
conceito just-in-time - apenas por um período de tempo x

![image](https://github.com/mariannaariel/SecurityGirls/assets/49196442/6541fc18-975a-4d75-8268-a26f94455fbc)

TDE (Banco de Dados)

Microsoft Defender para Nuvem 
Gerenciamento da postura de sergurança na nuvem CSPM secure score 
CWP proteção de carga de trabalho 
Just in time

Microsoft Cloud Security Benchmark 
lista de recomendações para o ambiente azure 

Microsoft Sentinel 
SIEM gerenciamento de eventos e incidentes de segurança, conectar diferentes fontes de dados de sua plataforma ambiente.
SOAR auxiliar a tratativa dos incidentes 
Coleta dos dados  
Detectar possíveis anomalias
investigar possivel incidentes
resposta 

Microsoft 365 Defender 
Usuário final 
Microsoft Defender para Identidade Micrososft Defender para Pontos de Extreminade Microsoft Defender for Cloud Apps Microsoft Defender para Office 365

Microsoft Defender para Identidade usado para usuários locais do ad 
Microsoft Defender for Cloud Apps shadow it 

Microsoft Defender para Plano 1 Microsoft plano 2
![image](https://github.com/mariannaariel/SecurityGirls/assets/49196442/a5070913-5063-4bde-abdc-6f2c17536a90)

Rastreadores de ameaças e gerenciador de ameaças
AIR (Investigação e resposta automatizadas)
Simulador de ataque
Busca proativa de ameaças 
Investigação de incidentes e alertas
![image](https://github.com/mariannaariel/SecurityGirls/assets/49196442/91259b22-78ac-4746-918c-1d1aaab7b0f5)
