# Template Aerohive Network
Model: AP-250
Dell Network

Monitoramento de rede aerohive access point


Desenvolvimento utilizando snmpwalker, sniffer.
Implementações em zabbix, linux CentOS

# Resumo

Template criado utilizando versão de firmware dos APs 10.0r7a, é possivel que algo muito fora disso apresente informações diferentes. 

-> Valores mapeados foram utilizados para diagnosticar o canal que o cliente está trabalhando, 2.4 ou 5Ghz.
-> Histórico de intensidade de sinal do registro mantido por 7 dias para analise de disponibilidade.
-> Checagem por segundo e multiplicação de bits foram usadas para definir o trafico nas interfaces.

Estou disponivel para esclarecer duvidas via email: geeksleo@gmail.com

# Dados coletados.

Clientes listados por MAC e monitorado por dbm
![](https://github.com/leosec/template_aerohive_network/blob/master/Clients.PNG)

Trafico por interface
![](https://github.com/leosec/template_aerohive_network/blob/master/Interfaces.PNG)

SSIDs removidos por segurança.
![](https://github.com/leosec/template_aerohive_network/blob/master/SSIDs.png)
