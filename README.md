# Iniciando na UItecnologia
  Neste documento, você encontrará as etapas para iniciar o desenvolvimento, divididas em duas partes: 
configurar as ferramentas necessárias e preparar o ambiente de desenvolvimento.

# Configurando Ferramentas
Nesta seção, abordaremos todas as ferramentas utilizadas na empresa e faremos os cadastros utilizando o e-mail disponibilizado.

## Requisitos
* Bitbucket
* Jira
* Slack

# Configurando o Ambiente

## Requisitos
* Git
* Node
* Yarn
* Postgres

# Resolvendo Problemas
Esta seção aborda possiveis problemas durante o processo de configuração do ambiente.

## Problema com biblioteca de conexão com o Postgres do PHP

* Vá a pasta em que o PHP está instalado.
* Na pasta apache2, abra o arquivo php.ini.
* Descomente as linhas extension=pdo_pgsql

***Nota:** Esse problema pode acontecer com qualquer biblioteca, sempre for necessário habilitar uma nova o mesmo processo deve ser executado,
basta descomentar outras linhas.

