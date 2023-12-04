# Iniciando na UItecnologia
  Neste documento, você encontrará as etapas para iniciar o desenvolvimento, divididas em duas partes: 
configurar as ferramentas necessárias e preparar o ambiente de desenvolvimento.

# Configurando Ferramentas
Nesta seção, abordaremos todas as ferramentas utilizadas na empresa e faremos os cadastros utilizando o e-mail disponibilizado.

## Requisitos
* Umbler
* Bitbucket
* Jira
* Slack

## Etapas
Após receber o e-mail da empresa, acesse o Umbler e faça o registro nas ferramentas listadas acima.

* O registro do Jira e Bitbucket é o mesmo, use o mesmo login para ambos.

### Registrando chave ssh
1. Execute o comando `ssh-keygen -t rsa` para gerar a chave, pode pressionar enter em todas as etapas.
2. use code


# Configurando o Ambiente
Esta seção aborda as ferramentas de desenvolvimento que são utilizadas na empresa.

## Requisitos
* Node
* Yarn
* Postgres
* PHP (versão 7.4.3)
* VsCode
* DBeaver
* Angular cli
* Git

## Instruções
* Instale as ferramentas essenciais seguindo as instruções específicas de cada uma.
* Se enfrentar problemas, consulte a seção "Resolvendo Problemas" para orientações.
* Recomendamos a utilização do ChatGPT para uma configuração rápida e suporte personalizado. Se encontrar dificuldades, o ChatGPT está disponível para ajudar durante o processo de configuração.

# Resolvendo Problemas
Esta seção aborda possíveis problemas durante o processo de configuração do ambiente.

## Problemas com a Biblioteca de Conexão com o Postgres no PHP

Para resolver problemas de conexão com o Postgres no PHP, siga estas etapas:

1. Navegue até a pasta de instalação do PHP.
2. Localize a pasta 'apache2' e abra o arquivo 'php.ini'.
3. Descomente a linha 'extension=pdo_pgsql'.

***Nota:** Este problema pode surgir com outras bibliotecas. Sempre que for necessário habilitar uma nova, repita o mesmo processo descomentando as linhas relevantes no arquivo 'php.ini'.***

## Alterando senha do postgres
execute os comandos:
1. `sudo -u postgres psql`
2. `ALTER USER postgres PASSWORD '123456';`

## Adicionando bitbucket ao Known Hosts
execute as etapas:
1. cd ~/.ssh/
2. code known_hosts
3. Apagar conteúdo do arquivo
4. ssh-keyscan -t rsa bitbucket.org >> ~/.ssh/known_hosts












