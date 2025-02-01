##Comandos Gerais de Troubleshooting

Azul função, Vermelho comando, Laranja tópico.
*********************************************************************
Verificar a Conectividade Básica:

Ping:
ping <endereço-ip>
Testa a conectividade com um endereço IP.
*********************************************************************
Traceroute:
tracert <endereço-ip>
Exibe o caminho que os pacotes seguem até o destino.
*********************************************************************
Verificar Interfaces e Links:
Status da Interface:
display interface <interface-name>
Exibe o status e estatísticas da interface.

Verificar Interfaces de VLAN:
display interface vlan <vlan-id>

Verificar Tabela de Roteamento:
Tabela de Roteamento Geral:
display ip routing-table
Mostra todas as rotas IP na tabela de roteamento.

Tabela de Roteamento IPv6:
display ipv6 routing-table
*********************************************************************


Verificar Protocolos de Roteamento:

Estado do OSPF:
display ospf peer
Exibe o estado dos vizinhos OSPF.

Base de Dados OSPF:
display ospf database

Estado do BGP:
display bgp peer

Sessões BGP:
display bgp vpnv4 unicast peer
Verificar Logs e Eventos do Sistema:

Verificar rotas recebidas de um vizinho BGP com IP 192.168.1.1:
display bgp peer 192.168.1.1 received-routes
Este comando exibe todas as rotas que foram recebidas do vizinho BGP com o IP 192.168.1.1.

Verificar rotas enviadas para um vizinho BGP com IP 192.168.1.1:
display bgp peer 192.168.1.1 advertised-routes
Este comando exibe todas as rotas que foram anunciadas para o vizinho BGP com o IP 192.168.1.1.

*********************************************************************



Logs do Sistema:
display logbuffer
Exibe o buffer de logs do sistema para eventos e erros.

Logs Específicos de OSPF:
display logbuffer | include ospf

Logs Específicos de BGP:
display logbuffer | include bgp

Verificar Estado do Sistema:
Uso da CPU e Memória:
display cpu-usage
display memory

Informações do Sistema:
display version
display uptime
*********************************************************************

Verificar e Diagnosticar Problemas de Roteamento:

Verificar a Rota para um Destino Específico:
display ip routing-table <destino>

Verificar a Origem da Rota e Detalhes:
display ip routing-table <prefix> detailed



*********************************************************************
Verificar Conectividade e Caminho de Dados:

Ping com Tamanho de Pacote Específico:
ping <endereço-ip> -s <tamanho>

Ping Traceroute:
tracert <endereço-ip> -h <número-de-hop>

Mostrar Configuração de Interface:
display current-configuration interface <interface-name>

Mostrar Configuração OSPF:
display current-configuration ospf

Mostrar Configuração BGP:
display current-configuration bgp

Verificar se a interface está ativa e em funcionamento:
display interface brief

Verificar erros e contadores de interface:
display interface <interface-name> statistics

Verificar o estado da conexão BGP e rotas BGP recebidas:
display bgp peer <ip-address> summary

Verificar o estado do OSPF e vizinhos OSPF:
display ospf peer



By: Guilherme Matozo
Linkedin: https://www.linkedin.com/in/guilherme-matozo-8669b91a4/
Comandos Gerais de Troubleshooting

Azul função, Vermelho comando, Laranja tópico.
*********************************************************************
Verificar a Conectividade Básica:

Ping:
ping <endereço-ip>
Testa a conectividade com um endereço IP.
*********************************************************************
Traceroute:
tracert <endereço-ip>
Exibe o caminho que os pacotes seguem até o destino.
*********************************************************************
Verificar Interfaces e Links:
Status da Interface:
display interface <interface-name>
Exibe o status e estatísticas da interface.

Verificar Interfaces de VLAN:
display interface vlan <vlan-id>

Verificar Tabela de Roteamento:
Tabela de Roteamento Geral:
display ip routing-table
Mostra todas as rotas IP na tabela de roteamento.

Tabela de Roteamento IPv6:
display ipv6 routing-table
*********************************************************************


Verificar Protocolos de Roteamento:

Estado do OSPF:
display ospf peer
Exibe o estado dos vizinhos OSPF.

Base de Dados OSPF:
display ospf database

Estado do BGP:
display bgp peer

Sessões BGP:
display bgp vpnv4 unicast peer
Verificar Logs e Eventos do Sistema:

Verificar rotas recebidas de um vizinho BGP com IP 192.168.1.1:
display bgp peer 192.168.1.1 received-routes
Este comando exibe todas as rotas que foram recebidas do vizinho BGP com o IP 192.168.1.1.

Verificar rotas enviadas para um vizinho BGP com IP 192.168.1.1:
display bgp peer 192.168.1.1 advertised-routes
Este comando exibe todas as rotas que foram anunciadas para o vizinho BGP com o IP 192.168.1.1.

*********************************************************************



Logs do Sistema:
display logbuffer
Exibe o buffer de logs do sistema para eventos e erros.

Logs Específicos de OSPF:
display logbuffer | include ospf

Logs Específicos de BGP:
display logbuffer | include bgp

Verificar Estado do Sistema:
Uso da CPU e Memória:
display cpu-usage
display memory

Informações do Sistema:
display version
display uptime
*********************************************************************

Verificar e Diagnosticar Problemas de Roteamento:

Verificar a Rota para um Destino Específico:
display ip routing-table <destino>

Verificar a Origem da Rota e Detalhes:
display ip routing-table <prefix> detailed



*********************************************************************
Verificar Conectividade e Caminho de Dados:

Ping com Tamanho de Pacote Específico:
ping <endereço-ip> -s <tamanho>

Ping Traceroute:
tracert <endereço-ip> -h <número-de-hop>

Mostrar Configuração de Interface:
display current-configuration interface <interface-name>

Mostrar Configuração OSPF:
display current-configuration ospf

Mostrar Configuração BGP:
display current-configuration bgp

Verificar se a interface está ativa e em funcionamento:
display interface brief

Verificar erros e contadores de interface:
display interface <interface-name> statistics

Verificar o estado da conexão BGP e rotas BGP recebidas:
display bgp peer <ip-address> summary

Verificar o estado do OSPF e vizinhos OSPF:
display ospf peer



By: Guilherme Matozo
Linkedin: https://www.linkedin.com/in/guilherme-matozo-8669b91a4/
