#  Relatório Técnico de Pentest – Desafio Final (Módulo 3 – Ethical Hacking)
##   FORMAÇÃO CYBERSEC - *Kensei Cybersec / Vai na Web*

Este repositório contém o relatório técnico produzido para o desafio final do Módulo 3 – Ethical Hacking  
O objetivo foi realizar um PenTest autorizado em dois ambientes distintos, identificar vulnerabilidades, capturar flags e documentar metodologias e achados.

---

## 1.Objetivo
O relatório apresenta:
- Enumeração de portas, serviços e diretórios.
- Identificação de vulnerabilidades reais (SQLi, LFI, falhas de autenticação, cookies inseguros etc.).
- Análise de respostas da API, comportamento do navegador e inspeção de código.
- Registro detalhado das flags capturadas.
- Avaliação de riscos e recomendações finais.

---

## 2. Ambientes analisados
###  Ambiente 1 – Aplicação Web
- URL: `http://98.95.207.28`
- Tecnologias: Apache, MySQL, FTP, SSH.
- Vulnerabilidades exploradas: SQL Injection, Local File Inclusion, falhas de autenticação, credenciais expostas.

### Ambiente 2 – API REST 
- URL: `http://98.88.106.35:5000`
- Vulnerabilidades exploradas: falhas de autenticação JWT e desserialização insegura (RCE não concluída devido a bloqueios).

---

## 3. Quantidade de flags encontradas
O ambiente disponibilizava **16 flags**.  
Foram encontradas e documentadas **10 flags**, utilizando:

- enumeração de portas e diretórios  
- inspeção de código HTML/CSS/JS  
- DevTools (Network, Application, Cookies)  
- Nmap, Gobuster, curl, MetaSploit 
- SQLi, LFI, autenticação fraca  
- observação de respostas da API  

---

## 4. Conteúdo do relatório
O documento inclui:

- Introdução  
- Metodologia (OWASP + PTES)  
- Escopo dos ambientes  
- Descobertas técnicas  
- Análise de risco  
- Conclusão  
- Recomendações  
- Tabela de flags capturadas  
- Anexos com evidências

---

## 6. Como visualizar
Abra o PDF diretamente no navegador ou baixe o arquivo.
 
--- 
## Licença e Ética 
Este projeto foi desenvolvido *exclusivamente para fins educacionais* em  ambientes autorizados.

---
