# Integração Zabbix-OTRS


O objetido do presente projeto é integrar as ações das triggers de alertas do zabbix com os chamados do otrs, concluindo os chamados quando os incidentes são normalizados. 


# Conteúdo

  - Codigo em Python do serviço desenvolvido para criar os chamados no OTRS, utilizando a biblioteca Python-Otrs
  - Código do serviço em Perl responsável pelo fechamento dos chamados quando for acionado.
  - Ações de abertura e fechamento a serem adicionados as triggers no zabbix.

### Instalação

Para a utilização se faz necessária a instalação de todas as dependencias do pyhton e do perl que forem necessárias  ( vai ser sempre requerido, como o libsoap-lite do perl ou python-otrs no python).
depois basta colocar os scripts no servidor do zabbix, e adicionar as ações nas triggers para executar o comendo e personalizar  de acordo com a necessidade.

