# Desafio Prático DIO – Teste de Força Bruta com Medusa

Descrição:
Projeto para o desafio da DIO: simulação de ataques de força bruta em ambiente controlado (Kali + Metasploitable2 + DVWA).

Ferramentas:
- Kali Linux
- Metasploitable 2
- DVWA (Damn Vulnerable Web Application)
- Medusa
- Git / GitHub

Objetivo:
Demonstrar ataques de força bruta em serviços (FTP, Web, SMB) e documentar evidências e recomendações de mitigação.

Passo a passo (resumo):
1) Configuração do ambiente: Kali (atacante) e Metasploitable2 (alvo) na mesma rede.
2) Coleta de evidências: ss, logs de apache, vsftpd, etc.
3) Testes manuais: FTP (curl), DVWA (curl POST), SMB (smbclient).
4) Registro dos resultados em results.csv e cópia das evidências para images/.

Evidências:
- images/target_logs/ss_target_*.txt
- images/target_logs/apache_access_after_dvwa_*.txt
- images/dvwa_attempt_*.html
- images/ftp_attempt_*.txt

Mitigações recomendadas:
- Implementar bloqueio por tentativas (fail2ban)
- Rate limiting / CAPTCHA em formulários de login
- Uso de HTTPS/TLS e políticas de senha fortes
- Monitoramento e alertas para múltiplas falhas

Autor: Francisco Carvalho (carwalho)
