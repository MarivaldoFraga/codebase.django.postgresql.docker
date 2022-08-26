# Aplicação Web Django Genérica com PostgreSQL em Docker
A inicialização deste ambiente requer a instalação dos softwares Docker e Windows Linux Subsystem - WLS.

## Iniciar os serviços
> docker-compose up <br>
> docker-compose exec web sh -c "python manage.py migrate" <br>

## Observações
O diretório de dados do PostgreSQL não está versionado.

## Referências
https://docs.docker.com/samples/django/