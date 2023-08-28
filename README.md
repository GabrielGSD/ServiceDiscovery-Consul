# ServiceDiscovery-Consul

Rodando o consul como agent em um ambiente de dev
> consul agent -dev

Consultar todos os consul que fazem parte do meu cluster   
> consul members 

Trabalhando com servidor DNS do próprio Consul (instalar ele)
> apk -U add bind-tools
> dig @<ip> -p 8600
> dig @localhost -p 8600 consul01.node.consul