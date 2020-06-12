# Docker - Servidor Laravel e MySQL

### Requisitos

Internet
Docker

### Uso

Conteiner criado para trabalhar com Laravel e MySQL.

### Como instalar.

1. Clone este repositório do git no seu computador.

   > git clone https://github.com/netocosta/docker-laravel-mysql.git

2. Descompacte o arquivo "laravel_sample.zip".

   > unzip laravel_sample.zip

3. Levante os conteiners, o docker-compose irá baixar as imagens.

   > docker-compose up -d

4. Será necessário gerar a appkey do laravel. Execute o seguinte comando.

> docker exec laravel-app php artisan key:generate

Pronto, seu servidor laravel e o laravel já estão configurados e pronto para uso.
Acesse: http://localhost:8000/

### O que temos

O servidor laravel está configurado para rodar na porta 8000.
O servidor MySQL está configurado para rodar na porta padrão 3306.

### Como acessar.

Acesse pelo navegador: http://localhost:8000/

### Arquivo / Função

| Arquivo            | Função                    |
| ------------------ | ------------------------- |
| docker-compose.yml | Arquivo do docker-compose |
| laravel_sample.zip | Codigo-fonte do laravel   |
| README.md          | README do git.            |

### Volumes do Docker

O docker-compose está configurado para que os arquivos principais sejam "hospedados" no seu computador. Ou seja, se a qualquer momento você quiser remover os containers, suas alterações no banco de dados e nos arquivos do php5 e php7, ainda estarão disponíveis.

A qualquer momento, basta efetuar o passos 3 e 4 do "Como Instalar" e tudo estará funcionando da mesma maneira.

### Dúvidas?

> Neto Costa - netocjp@gmail.com

# Faça bom uso
