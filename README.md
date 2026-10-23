# Wazuh Enterprise Baseline 2026 - 17 Regras MITRE ATT&CK

> Baseline de detecção usado em SOCs L1/L2 em 2026. 17 regras custom de alta fidelidade cobrindo as principais técnicas de ataque atuais, incluindo zero-day PHP2Shell de Out/2026.

**Autor:** Filipe Gabriel | SOC Analyst | Luanda, AO
**Wazuh Version:** 4.8+ | **MITRE ATT&CK:** v14
**Última atualização:** 23 Out 2026 - Adicionado PHP2Shell CVE-2026-109618

### 🎯 Tabela de Detecção

| Rule ID | Técnica MITRE | O que Detecta | Level |
| :--- | :--- | :--- | :--- |
| 100001 | T1070.001 | Clear Event Logs - Hacker apagando rastro | 12 |
| 100002 | T1053.005 | Scheduled Task - Persistência | 12 |
| 100003 | T1059.001 | PowerShell Ofuscado - Bypass, Base64 | 12 |
| 100004 | T1003.001 | LSASS Dump - Mimikatz | 15 |
| 100005 | T1566.001 | Office -> Shell - Phishing | 15 |
| 100006 | T1105 | LOLBins - certutil/bitsadmin | 12 |
| 100007 | T1048 | Exfiltração - rclone/megasync | 12 |
| 100008 | T1087 | Recon AD - SharpHound | 10 |
| 100009 | T1110.001 | Brute Force - 10 falhas em 2 min | 10 |
| 100010 | T1110.001 | Brute Force Sucesso - Invasão | 15 |
| 100011 | T1110 | RDP Externo - LogonType 10 | 10 |
| 100012 | T1136.001 | Novo usuário criado | 12 |
| 100013 | T1098 | Usuário virando Admin | 15 |
| 100014 | T1003 | Comando Mimikatz - sekurlsa | 15 |
| 100015 | T1562.001 | Desativando Defender / EDR | 15 |
| **100016**
