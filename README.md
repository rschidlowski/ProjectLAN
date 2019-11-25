# ProjectLAN

Projeto Redes - Hackatlhon

Topologia: ponto a ponto (peer-to-peer)
Matriz: Como a empresa possui muitos recursos, deverão ser criados VLANS para subdividir o endereçamento dos equipamentos da rede local, sendo:
roteador/servidores: 10.1.1.0 ~ 10.1.1.10
switchs/aps/impressoras/celulares: 10.1.1.11 ~ 10.1.1.50
Desktops: Vlan1_DESK (10.2.1.10 ~ 10.2.1.250)
Notebooks: Vlan2_NOT (10.3.1.10 ~10.3.1.50)
Segurança de Rede:
Usuários/equipamentos
Restrição de acesso, instalação e alteração poderão ser realizados  atraves de  diretivas de politicas de grupo (GPO) do Microsoft Windows 2016. Como sugestão para inibir o uso de dispositivos removiveis recomendo o Antivirus TrendMicro. 
O acesso entre matriz e filiais se derá atraves de VPN. Como sugestão para acesso VPN entre as empresas utilizaria o Appliance Firewall  Fortigate 100E para Matriz e Fortigate 60E para Filiais
Para o funcionamento dos sistemas e recursos as seguintes portas deverão ser liberadas;
WEB não criptografada: 80 HTTP
WEB cripotgrafada: 443 TCP
 IMAP4: 143 TCP / 993 TCP
POP3: 110 TCP / 995 TCP
SMTP: 587 TCP
Oracle Server: 1158 TCP / 5500 TCP
Oracle Conection Manager: 1630 TCP
Oracle Data Guard: 1521 TCP
Oracle Agent: 3938 HTTP
Filial Florianopolis
Endereçamento IP
Roteador: 10.4.1.1
Firewall/VPN: 10.4.1.2 
Switches/AP: 10.4.1.3 ~ 10.4.1.9
Servidor: 10.4.1.10
Impressoras: 10.4.1.11 ~ 10.4.1.14
Desktops/notebooks/celulares: 10.4.1.20 ~ 10.4.1.253
 
Filial Porto Alegre
Endereçamento IP
Roteador: 10.5.1.1
Firewall/VPN: 10.5.1.2 
Switches/AP: 10.5.1.3 ~ 10.5.1.9
Servidor: 105.1.10
Impressoras: 10.5.1.11 ~ 10.5.1.16
Desktops/notebooks/celulares: 10.5.1.20 ~ 10.5.1.253
