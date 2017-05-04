# php docker compose


## #Executando

Para dar deploy da aplicação de exempo faça o clone do repositório linkado.

Na pasta do clone, você deverá executar:

    docker-compose up -d

Este comando irá subir TODOS os serviços em modo background. Se você deseja subir apenas o serviço de web(nginx & php-fpm) deverá executar:

    docker-compose up -d web
