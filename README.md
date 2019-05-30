## Blog api

- Instalar Virtualenv

> virtualenv blog-api

- Instalar dependencias do projeto com:

> pip install -r requirements.txt

- Criar banco de dados postgres
> sudo su postgres
> psql
> CREATE DATABASE blog-api;
> CREATE ROLE seu-usuario SUPERUSER LOGIN PASSWORD '123456';
> ALTER TABLE DATABASE blog-api OWNER TO seu-usuario