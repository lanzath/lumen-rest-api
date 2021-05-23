# <p align="center"> Simple Lumen REST API

### Back-end
A REST API foi feita em [PHP 7.4](https://www.php.net/) e [Lumen](https://lumen.laravel.com/) e banco de dados [SQLite3](https://www.sqlite.org/index.html).

Para configuração na máquina local é necessário ter o [PHP 7.4](https://www.php.net/) e o [Composer](https://getcomposer.org/) instalados.

Crie na basta back-end o arquivo `.env` com o comando `cp .env.example .env`.

Com o terminal aberto na pasta back-end rode os seguintes comandos:

- `touch database/database.sqlite` 
- `composer install`
- `php artisan migrate --seed`

Para rodar o server local basta rodar o comando:
**`php -S localhost:8000 -t public`** conforme indica a documentação do [Lumen](https://lumen.laravel.com/docs/8.x#installation)
~~~
