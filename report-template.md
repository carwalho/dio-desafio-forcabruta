# Relatório — Desafio DIO: Força Bruta (Kali + Metasploitable2)

## Resumo executivo
(Objetivo, ambiente e conclusão resumida)

## Ambiente
- Kali Linux (atacante) — IP: 192.168.56.103
- Metasploitable2 (alvo) — IP: 192.168.56.102
- Ferramentas: Medusa, curl, smbclient, ss, Apache logs

## Metodologia
Descreva: configuração das VMs, rede (host-only/NAT), procedimentos de teste (limite de tentativas, coleta de logs).

## Evidências
- images/target_logs/ss_target_YYYYMMDDTHHMMSS.txt
- images/target_logs/apache_access_after_dvwa_YYYYMMDDTHHMMSS.txt
- images/dvwa_attempt_YYYYMMDDTHHMMSS.html
- images/ftp_attempt_YYYYMMDDTHHMMSS.txt

## Resultados
Inclua linhas do results.csv e análise (ex.: 1 tentativa FTP falhou, 1 tentativa DVWA falhou, sem lockout observado).

## Recomendações de mitigação
- fail2ban / bloqueio por IP
- CAPTCHAs e rate-limit na aplicação web
- Forçar TLS/HTTPS
- Políticas de senha e monitoramento

## Conclusão
(Resumo final e próximos passos de melhoria)

