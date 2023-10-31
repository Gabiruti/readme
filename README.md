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

## Problemas com a Biblioteca de Conexão com o Postgres no PHP

Para resolver problemas de conexão com o Postgres no PHP, siga estas etapas:

1. Navegue até a pasta de instalação do PHP.
2. Localize a pasta 'apache2' e abra o arquivo 'php.ini'.
3. Descomente a linha 'extension=pdo_pgsql'.

***Nota:** Este problema pode surgir com outras bibliotecas. Sempre que for necessário habilitar uma nova, repita o mesmo processo descomentando as linhas relevantes no arquivo 'php.ini'.***

