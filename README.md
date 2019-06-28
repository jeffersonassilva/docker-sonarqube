# Sonar Docker
## Antes de rodar os comandos do docker é preciso configurar as variáveis de ambiente.
### Existem algumas configurações pré definidas, com isso basta executar o comando abaixo:
    cp example.env .env
## Depois de configurar as variáveis de ambiente basta rodar o docker-compose conforme cada ambiente.
### Rodar aplicação localmente
    docker-compose up --build
### Rodar aplicação em ambiente de produção
    docker-compose up --build -d
### Senha de acesso do sonarqube
    login: admin
    senha: admin