# Firewall do Mercado

Simulador de firewall para aula (Gestão de Redes e CiberSegurança, Técnico em Informática).
Um único `index.html`, sem servidor e sem dados de alunos. O progresso fica no navegador de quem usa. O arquivo `.fwm` também guarda o estado assinado (linha `ESTADO`), e a aba Relatório permite continuar a partir dele, só com nome e matrícula idênticos aos do aluno logado.

A dupla assume a TI de um mercado com loja online (DMZ), servidores, câmeras, Wi-Fi de visitantes e home office.
Cria regras de permitir e bloquear, muda a ordem, troca a política padrão, libera a VPN WireGuard e liga o IDS/IPS,
enquanto o tráfego ao vivo mostra o que passa e o que é barrado. Oito missões são conferidas na hora.
