<hr />

<h1>Integración de Laravel 11 con Redis para implementación de colas usando Docker y docker-compose</h1>
<h1>Aprovisionamiento para despliegue en AWS con EC2 (Elastic Compute Cloud) y RDS (Relational Database Service )</h1>
<h2>PHP 8.3.14</h2>
<h2>Laravel 11.35.0</h2>
<h2>Docker 27.2.0</h2>
<h2>Docker compose 3.8</h2> 
<h3>Todo preparado para implementar un CD/CI bajo algún servidor de integración continua como Jenkins por ejemplo</h3>

#instalar contenedor<br/>
<code>docker-compose up --build</code>
<hr />
#entrar a la consola
<br/>
<code>docker exec -it peligro-laravel-app bash</code>
<hr />
#detener proyecto
<br/>
<code>docker-compose down</code>
<hr />
#ejecutar las colas con supervisor
<br/>
<code>docker exec -it peligro-laravel-app service supervisor start</code>

