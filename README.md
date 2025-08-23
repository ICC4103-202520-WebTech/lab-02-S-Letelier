# README
Dependencias del sistema:

-Ubuntu

-Git

-Ruby via rbenv or rvm

-PostgreSQL server running locally

--------------------------------------------

Versiones necesarias:

-Ruby Versión: 3.4.3

-Rails Versión: 8.0.2.1

Para comprobar las versiones corre en la terminal de Ubuntu lo siguiente:

ruby -v       
rails -v      
     


En caso de no tener estas versiones, corre en la terminal de Ubuntu lo siguiente:


rbenv install 3.4.3

rbenv global 3.4.3

gem install rails -v 8.0.2.1

--------------------------------------------

Pasos de la instalación y ejecución (todo debe hacerse en la terminal de Ubuntu):

1- Clona el repositorio:

git clone https://github.com/ICC4103-202520-WebTech/lab-02-S-Letelier.git

2- debería aparecer "lab-02-S-Letelier" comprueba si se clono perfectamente usando: 

ls

3- Accede a la carpeta con lo siguiente:

cd lab-02-S-Letelier

4- luego instala el bundle:

bundle install

5- genera el servidor de rails:

rails db:create

6- abre el servidor con:

rails s

7- en tu navegador en la barra superior de búsqueda ingresa lo siguiente:

http://localhost:3000/about

8- con eso quedaria todo fino fino
