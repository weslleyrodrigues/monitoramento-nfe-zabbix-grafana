# Monitoramento-Nfe-zabbix-grafana
Melhoramos esse shellscript com base no artigo do Bernardo Lankheet, onde o mesmo ensina e disponibiliza os códigos para monitorar os status das NFEs dos autorizadores da SEFAZ com o Zabbix, mas somente os WebServices Versões 3.10 ou anteriores.  Como ultimamente surgiu a necessidade de monitorar a versão 4.00, o mesmo código não dava suporte, tomamos então a liberdade, (Eu, juntamente ao https://github.com/marcioaraujo01) de modificar e compartilhar este script com a comunidade, para quem precisar monitorar a NFE 4.00. Passamos assim a monitorar os novos autorizadores e integramos os dados com o grafana, criando, gráficos, alertas e etc, quando algum serviço da SEFAZ estiver indisponível. O procedimento para implementação não ensinaremos, pois o mesmo se encontra no link do desenvolvedor. (https://www.bernardolankheet.com.br/monitorando-status-de-servio-nfe-da-sefaz-com-zabbix/) *Link Indisponivel

A Implementação é simples, basta copiar este arquivo substituindo o original. sefaz.consulta.nfe 


