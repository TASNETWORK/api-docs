---
categories:
- My Job
---
# Plesk 

  

 ✔  Usado

❌ No usado

⭕ Usado sin SSL o no muestra nada

🔄 Redirect

  

### Containers

  

|     |     |     |     |
| --- | --- | --- | --- |
| Nombre | Imagen | Dockerfile | Jenkinfile |
| Jenkins | custom/jenkins | ✔   | ❌   |
| Mongodb | mongo:5.0.0 | ❌   | ❌   |
| Mysql | mysql | ❌   | ❌   |
| Redis | redis:latest | ❌   | ❌   |
| rendertron-seo | dockette/rendertron | ❌   | ❌   |
| travelerassitance\_api\_blog\_production | travelerassistance/nest/api-blog:production | ✔   | ✔   |
| travelerinsurance\_builder\_development | travelerinsurance/laravel/builder:development | ✔   | ✔   |
| travelerinsurance\_builder\_production | travelerinsurance/laravel/builder:production | ✔   | ✔   |
| travelinsurance\_api\_development | travelinsurance/netcore/api:development | ✔   | ✔   |
| travelinsurance\_api\_production | travelinsurance/netcore/api:production | ✔   | ✔   |
| travelinsurance\_supernova\_development | **travelinsurance/angular/supernova:development** | ✔   | ✔   |
| travelinsurance\_supernova\_production | travelinsurance/angular/supernova:production | ✔   | ✔   |
| vistravelcenter\_api\_development | vistravelcenter/laravel/api:development | ✔   | ✔   |
| vistravelcenter\_api\_production | vistravelcenter/laravel/api:production | ✔   | ✔   |

  

  

* * *

  

### Persistence's

  

|     |     |     |     |     |
| --- | --- | --- | --- | --- |
| Nombre | ubicación contenedor | ubicación host | port internal | port external |
| Jenkins | 1. /var/run/docker.sock<br>2. /var/jenkins\_home | 1. /var/run/docker.sock<br>2. /home/ebenalczarespn/jenkins/data | 50000  <br>8080 | 50000  <br>25001 |
| Mongodb | 1. /data/db<br>2. /docker-entrypoint-initdb.d/mongo-init.js | 1. /home/ebenalczarespn/mongo-db-persistent<br>2. /var/jenkins\_home/workspace/travelerassistance-nest-api-blog-production/docker-entrypoint-initdb.d/mongo-init.js | 27017 | 27017 |
| MySQL | 1. /var/lib/mysql | 1. /home/ebenalczarespn/mysql-persistent | 3306  <br>33060 | 6612  <br>63120 |
| Redis | 1. /data | 1. /home/ebenalczarespn/docker-persistent/redis/data | 6379 | 6379 |
| rendertron-seo |     |     | 3000 | 3500 |
| travelerassitance\_api\_blog\_production |     |     | 3000 | 10100 |
| travelerinsurance\_builder\_development |     |     | 443  <br>80  <br>9000 | 12004  <br>12003 |
| travelerinsurance\_builder\_production |     |     | 80  <br>9000 | 10003 |
| travelinsurance\_api\_development | 1. /root/.microsoft/usersecrets<br>2. /app/App\_Data/Logs | 1. /home/ebenalczarespn/docker-persistent/netcore/travelerinsurance/api/development<br>2. /home/ebenalczarespn/docker-persistent/netcore/travelerinsurance/api/development/logs | 80  | 12001 |
| travelinsurance\_api\_production | 1. /root/.microsoft/usersecrets<br>2. /app/App\_Data/Logs | 1. /home/ebenalczarespn/docker-persistent/netcore/travelerinsurance/api/production<br>2. /home/ebenalczarespn/docker-persistent/netcore/travelerinsurance/api/production/logs | 80  | 10001 |
| travelinsurance\_supernova\_development |     |     | 80  | 12002 |
| travelinsurance\_supernova\_production |     |     | 80  | 10002 |
| vistravelcenter\_api\_development |     |     | 80  <br>9000 | 16001 |
| vistravelcenter\_api\_production |     |     | 80  <br>9000 | 14001 |

  

  

* * *

  

### Database

  

|     |     |     |     |
| --- | --- | --- | --- |
| #   | Nombre | Tamaño en MB | Uso |
| 1   | administrator | Vacio |     |
| 2   | apsc | 0.84375000 |     |
| 3   | belicese\_jos2 | 4.90150452 |     |
| 4   | chilespv\_jos1 | 5.01087952 |     |
| 5   | dev\_segurode\_dbprincipal | 463.15092850 |     |
| 6   | directus\_node | Vacio |     |
| 7   | dominica\_jos1 | 5.37674332 |     |
| 8   | horde | 5.84375000 |     |
| 9   | isicecua\_isic | 1.64559174 |     |
| 10  | isichond\_isic | 0.16121674 |     |
| 11  | landings\_spv\_dev | 0.23437500 |     |
| 12  | landings\_spv\_prod | 41.20312500 |     |
| 13  | panamasp\_jos1 | 5.24525452 |     |
| 14  | patitaseguras | 0.14062500 |     |
| 15  | pervspv\_wp | 9.13137054 |     |
| 16  | production\_paws | Vacio |     |
| 17  | psa | 6.85937500 |     |
| 18  | roundcubemail | 0.46875000 |     |
| 19  | segurode\_dbprincipal | 761.80161762 |     |
| 20  | seguropa\_jos2 | 5.35620880 |     |
| 21  | segurovi\_dbayuda | 3.54994488 |     |
| 22  | segurovi\_jos1 | 8.42414474 |     |
| 23  | spvhondu\_jos1 | 5.13587952 |     |
| 24  | svmundia | Vacio |     |
| 25  | svmundia\_dbseguro | 14.75079536 |     |
| 26  | svmundia\_restful | 7077.58126831 |     |
| 27  | svmundia\_restful\_dev | 25.34670639 |     |
| 28  | TAS\_Network\_db | 1502.65625000 |     |
| 29  | TAS\_Network\_db\_production | 1778.96875000 |     |
| 30  | TAS\_Network\_db\_stag | 1495.85937500 |     |
| 31  | tas\_network\_hang\_fire\_db | 584.31250000 |     |
| 32  | tas\_network\_hang\_fire\_db\_production | 1448.62500000 |     |
| 33  | tas\_network\_hang\_fire\_db\_stag | 0.26562500 |     |
| 34  | TAS\_Network\_New | 41.7 |     |
| 35  | TAS\_Network\_new | 41.7 |     |
| 36  | TAS\_Network\_new\_db | 5.10937500 |     |
| 37  | ticketsystem\_blsquito | 0.10937500 |     |
| 38  | ticketsystem\_centrosviajeros | 0.29687500 |     |
| 39  | ticketsystem\_cv | 0.06250000 |     |
| 40  | ticketsystem\_ec | 0.06250000 |     |
| 41  | ticketsystem\_libertad | 0.28125000 |     |
| 42  | ticketsystem\_pereira | 0.06250000 |     |
| 43  | ticketsystem\_rocafuente | 0.18750000 |     |
| 44  | ticketsystem\_urd | 0.18750000 |     |
| 45  | traveler\_app | 6.69691563 |     |
| 46  | traveler\_dbayuda | 2.10068035 |     |
| 47  | traveler\_fenix | 0.31250000 |     |
| 48  | traveler\_joomla | 8.77666283 |     |
| 49  | traveler\_joomla\_dev | 8.51430702 |     |
| 50  | traveler\_principal | 184.18850422 |     |
| 51  | traveler\_principal\_dev | 117.11923695 |     |
| 52  | traveler\_prueba\_principal | 48.97770023 |     |
| 53  | traveler\_reembolsos | 9.04687500 |     |
| 54  | uruguays\_jos1 | 5.42028046 |     |
| 55  | venezuel\_jos1 | 5.16712952 |     |
| 56  | visatravelcenter\_development | 0.03125000 |     |
| 57  | visatrav\_simod | 103.75515652 |     |
| 58  | visatrav\_simod\_dev | 27.25614452 |     |
| 59  | wwwsegur\_jos1 | 4.81090927 |     |

  

  

* * *

  

### Domains & Subdomains  | 172.24.16.124

  

|     |     |     |
| --- | --- | --- |
| Nombre | Uso | Dockerfile |
| [admin.seguroparaviaje.com](https://admin.seguroparaviaje.com/) | ⭕   | ❌   |
| [api-blog.prod.traveler-assistance.com](https://api-blog.prod.traveler-assistance.com/) | ✔   | ✔   |
| [api.development.seguroparaviaje.com](https://api.development.seguroparaviaje.com/swagger/index.html) | ✔   | ✔   |
| [api.production.seguroparaviaje.com](https://api.production.seguroparaviaje.com/swagger/index.html "https://api.production.seguroparaviaje.com/swagger/index.html") | ✔   | ✔   |
| - [api-sandbox.visatravelcenter.com](https://api-sandbox.visatravelcenter.com/)<br><br>    - [output.visatravelcenter.com](https://output.visatravelcenter.com/) | ✔  <br>✔ | ✔  <br>✔ |
| [aws-dev-odoo.traveler-assistance.com](https://aws-dev-odoo.traveler-assistance.com/) | ✔   | ✔   |
| [aws-odoo.traveler-assistance.com](https://aws-odoo.traveler-assistance.com/) | ✔   | ✔   |
| [builder.seguroparaviaje.com](https://builder.seguroparaviaje.com/login) | ✔   | ✔   |
| [dev-landings.seguroparaviaje.com](https://dev-landings.seguroparaviaje.com/login) | ✔   | ❌   |
| [dev-odoo.traveler-assistance.com](http://dev-odoo.traveler-assistance.com/) | ⭕   | ❌   |
| [jenkins.seguroparaviaje.com](https://jenkins.seguroparaviaje.com/login?from=%2F) | ✔   | ✔   |
| [odoo.traveler-assistance.com](http://odoo.traveler-assistance.com/) | ⭕   | ❌   |
| [rendertron.seguroparaviaje.com](https://rendertron.seguroparaviaje.com/) | ✔   | ❌   |
| [seguroparaviaje.org](http://seguroparaviaje.org/) | ❌   | ❌   |
| [supernova.development.seguroparaviaje.com](https://supernova.development.seguroparaviaje.com/account/login) | ✔   | ✔   |
| [supernova.production.seguroparaviaje.com](https://supernova.production.seguroparaviaje.com/account/login) | ✔   | ✔   |

  

  

  

  

* * *

  

### Domains & Subdomains | 172.24.16.125

  

|     |     |     |     |
| --- | --- | --- | --- |
| **Nombre** | Uso | Front-end | Back-end |
| [1y2.me](http://1y2.me/) | ⭕   | ✔   | ❌   |
| [angular.seguroparaviaje.com  <br>](http://angular.seguroparaviaje.com/) | ⭕   | ✔   | ❌   |
| - [assistnetcard.com](https://assistnetcard.com/)<br><br>    - [dev](https://dev.assistnetcard.com/)<br>    - [staging](https://staging.assistnetcard.com/home) | ✔  <br>⭕  <br>⭕ | ✔  <br>✔  <br>✔ | ❌  <br>❌  <br>❌ |
| [comparaasist.com](https://www.comparaassist.com/) | ✔   | ✔   | ❌   |
| - [comparaassist.com](https://www.comparaassist.com/)<br><br>    - [admin](https://admin.comparaassist.com/)  <br>    <br>    - [api-compara](https://api-compara.comparaassist.com/)<br>    - [api-dev](https://api-dev.comparaassist.com/)<br>    - [assets](https://assets.comparaassist.com/)<br>    - [blog](https://blog.comparaassist.com/)<br>    - [dev](https://dev.comparaassist.com/)<br>    - [web-compara](https://web-compara.comparaassist.com/) | ✔  <br>✔  <br>⭕  <br>⭕  <br>⭕  <br>✔  <br>✔  <br>✔ | ✔  <br>✔  <br>❌  <br>❌  <br>✔  <br>✔  <br>✔  <br>✔ | ❌  <br>❌  <br>✔  <br>✔  <br>❌  <br>❌  <br>❌  <br>❌ |
| [doc24-7.com](https://doc24-7.com/) | ✔   | ✔   | ❌   |
| - [etiasrequisitos.com](https://etiasrequisitos.com/)<br><br>    - [api](https://api.etiasrequisitos.com/)<br>    - [dev](https://dev.etiasrequisitos.com/) | ✔  <br>✔  <br>✔ | ✔  <br>  <br>✔ | ❌  <br>❌  <br>❌ |
| [euroluzquito.com  <br>](https://euroluzquito.com/) | ❌❌  | ✔   | ❌   |
| [gosegurodeviaje.com](http://gosegurodeviaje.com/) | ❌   | ✔   | ❌   |
| [go-seguroparaviaje.com](http://go-seguroparaviaje.com/) | ❌   | ✔   | ❌   |
| - [isicecuador.ec](http://isicecuador.ec/)<br><br>    - [api](http://api.isicecuador.ec/) | ❌  <br>❌ | ✔  <br>❌ | ❌  <br>✔ |
| [isichonduras.hn](http://isichonduras.hn/) | ⭕   | ✔   | ❌   |
| - [patitaseguras.com](http://patitaseguras.com/ "http://patitaseguras.com/")<br><br>    - [api](http://api.patitaseguras.com/) | ❌  <br>❌ | ✔  <br>❌ | ❌  <br>✔ |
| - [pervolare.com](https://pervolare.com/)<br><br>    - [admin](https://admin.pervolare.com/)<br>    - [api-sandbox](https://api-sandbox.pervolare.com/)<br>    - [exchangerates](https://exchangerates.pervolare.com/)<br>    - [libphonenumber](https://libphonenumber.pervolare.com/) | ⭕  <br>⭕  <br>⭕  <br>✔  <br>✔ | ✔  <br>✔  <br>❌  <br>❌  <br>❌ | ❌  <br>❌  <br>✔  <br>✔  <br>✔ |
| [segurodeviageminternacional.com](https://www.segurodeviageminternacional.com/) | ✔   | ✔   | ❌   |
| [segurodeviajeacuba.com](http://segurodeviajeacuba.com/) | ⭕   | ✔   | ❌   |
| [segurodeviajemundial.cl](https://www.segurodeviajemundial.cl/) | ✔   | ✔   | ❌   |
| - [segurodeviajemundial.com](https://www.segurodeviajemundial.com/)<br><br>    - [assets](https://assets.segurodeviajemundial.com/)<br>    - [development](https://development.segurodeviajemundial.com/)<br>    - [dev](https://www.dev.segurodeviajemundial.com/)<br>    - [dev-sismod](https://www.dev-sismod.segurodeviajemundial.com/)<br>    - [email](https://email.segurodeviajemundial.com/login)<br>    - [emissions](https://emissions.segurodeviajemundial.com/)<br>    - [rest](https://rest.segurodeviajemundial.com/)<br>    - [sismod](https://www.sismod.segurodeviajemundial.com/) | ✔  <br>⭕  <br>⭕  <br>✔  <br>✔  <br>❌  <br>✔  <br>✔  <br>✔ | ✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>❌  <br>✔ | ❌  <br>❌  <br>❌  <br>❌  <br>❌  <br>❌  <br>❌  <br>✔  <br>❌ |
| [segurodeviajemundial.com.ar](https://www.segurodeviajemundial.com.ar/) | ✔   | ✔   | ❌   |
| [segurodeviajemundial.com.bo](https://www.segurodeviajemundial.com.bo/) | ✔   | ✔   | ❌   |
| [segurodeviajemundial.com.co](https://www.segurodeviajemundial.com.co/) | ✔   | ✔   | ❌   |
| [segurodeviajemundial.com.do](https://www.segurodeviajemundial.com.do/) | ✔   | ✔   | ❌   |
| [segurodeviajemundial.com.ec](https://www.segurodeviajemundial.com.ec/) | ✔   | ✔   | ❌   |
| [segurodeviajemundial.com.gt](http://segurodeviajemundial.com.gt/) | ❌   | ✔   | ❌   |
| [segurodeviajemundial.com.mx](https://www.segurodeviajemundial.com.mx/) | ✔   | ✔   | ❌   |
| [segurodeviajemundial.com.pa](https://www.segurodeviajemundial.com.pa/) | ✔   | ✔   | ❌   |
| [segurodeviajemundial.com.pe](https://www.segurodeviajemundial.com.pe/) | ✔   | ✔   | ❌   |
| [segurodeviajemundial.com.ve](https://www.segurodeviajemundial.com.ve/) | ✔   | ✔   | ❌   |
| [segurodeviajemundial.cr](https://www.segurodeviajemundial.cr/) | ✔   | ✔   | ❌   |
| [segurodeviajeparaecuador.com](https://www.segurodeviajeparaecuador.com/) | ⭕   | ✔   | ❌   |
| - [seguroparaviaje.biz](https://seguroparaviaje.biz/)<br><br>    - [code-server](https://code-server.seguroparaviaje.biz/)<br>    - [correo](https://correo.) | ✔  <br>❌  <br>❌ | ✔  <br>✔  <br>✔ | ❌  <br>❌  <br>❌ |
| [seguroparaviaje.bz](https://seguroparaviaje.bz/) | ✔   | ✔   | ❌   |
| [seguroparaviaje.cl](https://seguroparaviaje.cl/) | ✔   | ✔   | ❌   |
| - [seguroparaviaje.com](https://www.seguroparaviaje.com/)<br><br>    - [admin](https://admin.seguroparaviaje.com/)<br>    - [api](https://api.seguroparaviaje.com/)<br>    - [assets](https://assets.seguroparaviaje.com/)<br>    - [br.consulta](https://www.br.consulta.seguroparaviaje.com/)<br>    - [cms](https://cms.seguroparaviaje.com/public/admin/)<br>    - [consulta](https://consulta.seguroparaviaje.com/)<br>    - [core](https://core.seguroparaviaje.com/swagger/index.html)<br>    - [cotizador](https://cotizador.seguroparaviaje.com/)<br>    - [dashbard](https://dashbard.seguroparaviaje.com/)<br>    - [dev-api](https://dev-api.seguroparaviaje.com/)<br>    - [dev](https://www.dev.seguroparaviaje.com/)<br>    - [dev-tas-system](https://www.dev-tas-system.seguroparaviaje.com/)<br>    - [dlocal](https://dlocal.seguroparaviaje.com/)<br>    - [landings](https://landings.seguroparaviaje.com/login)<br>    - [masivo](https://masivo.seguroparaviaje.com/)<br>    - [navidad](https://navidad.seguroparaviaje.com/)<br>    - [new](https://new.seguroparaviaje.com/)<br>    - [rebranding](https://rebranding.seguroparaviaje.com/)<br>    - [rutaviajera](https://rutaviajera.seguroparaviaje.com/)<br>    - [sabrina](https://sabrina.seguroparaviaje.com/)<br>    - [sandbox-dash](https://sandbox-dash.seguroparaviaje.com/)<br>    - [sandbox](https://sandbox.seguroparaviaje.com/)<br>    - [sismod](https://sismod.seguroparaviaje.com/login/login.php)<br>    - [tas-system](https://www.tas-system.seguroparaviaje.com/)<br>    - [test](https://www.test.seguroparaviaje.com/)<br>    - [us.consultas](https://us.consultas.seguroparaviaje.com/)<br>    - [us](https://www.us.seguroparaviaje.com/)<br>    - [viajeros](https://viajeros.seguroparaviaje.com/)<br>    - [vidyo](https://vidyo.seguroparaviaje.com/) | ✔  <br>⭕  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>❌  <br>❌  <br>✔  <br>✔  <br>✔  <br>🔄  <br>✔  <br>✔  <br>❌✔  <br>✔  <br>✔  <br>✔  <br>⭕  <br>⭕  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>⭕ | ✔  <br>✔  <br>❌  <br>✔  <br>✔  <br>✔  <br>✔  <br>❌  <br>✔  <br>✔  <br>❌  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>❌  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔ | ❌  <br>❌  <br>❌  <br>❌  <br>❌  <br>✔  <br>❌  <br>✔  <br>❌  <br>❌  <br>✔  <br>✔  <br>❌  <br>❌  <br>✔  <br>❌  <br>❌  <br>❌  <br>❌  <br>✔  <br>❌  <br>❌  <br>✔  <br>❌  <br>❌  <br>❌  <br>❌  <br>❌  <br>❌  <br>❌ |
| [seguroparaviaje.com.ar](https://seguroparaviaje.com.ar/) | ✔   | ✔   | ❌   |
| [seguroparaviaje.com.bo](https://www.seguroparaviaje.com.bo/) | ✔   | ✔   | ❌   |
| - [seguroparaviaje.com.co](https://www.seguroparaviaje.com.co/)<br><br>    - [old](https://old.seguroparaviaje.com.co/) | ✔  <br>✔ | ✔  <br>✔ | ❌  <br>❌ |
| [seguroparaviaje.com.do](https://www.seguroparaviaje.com.do/) | ✔   | ✔   | ❌   |
| [seguroparaviaje.com.ec](https://www.seguroparaviaje.com.ec/) | ✔   | ✔   | ❌   |
| [seguroparaviaje.com.gt](https://www.seguroparaviaje.com.gt/) | ✔   | ✔   | ❌   |
| [seguroparaviaje.com.hn](https://www.seguroparaviaje.com.hn/) | ✔   | ✔   | ❌   |
| - [seguroparaviaje.com.mx](https://www.seguroparaviaje.com.mx/)<br><br>    - [dev](https://www.dev.seguroparaviaje.com.mx/) | ✔  <br>✔ | ✔  <br>✔ | ❌  <br>❌ |
| [seguroparaviaje.com.ni](https://seguroparaviaje.com.ni/) | ✔   | ✔   | ❌   |
| [seguroparaviaje.com.pa](https://seguroparaviaje.com.pa/) | ✔   | ✔   | ❌   |
| [seguroparaviaje.com.pe](https://seguroparaviaje.com.pe/) | ✔   | ✔   | ❌   |
| [seguroparaviaje.com.py](https://seguroparaviaje.com.py/) | ✔   | ✔   | ❌   |
| [seguroparaviaje.com.sv](https://seguroparaviaje.com.sv/) | ✔   | ✔   | ❌   |
| [seguroparaviaje.com.ve](https://seguroparaviaje.com.ve/) | ✔   | ✔   | ❌   |
| [seguroparaviaje.cr](https://www.seguroparaviaje.cr/) | ✔   | ✔   | ❌   |
| [seguroparaviaje.es](https://seguroparaviaje.es/) | ✔   | ✔   | ❌   |
| [seguroparaviaje.info](http://seguroparaviaje.info/) | ❌   | ✔   | ❌   |
| [seguroparaviaje.net](https://seguroparaviaje.net/) | ❌🔄 | ✔   | ❌   |
| [seguroparaviaje.org](http://seguroparaviaje.org/) | ❌   | ✔   | ❌   |
| [seguroparaviajes.net](https://seguroparaviajes.net) | ❌🔄 | ✔   | ❌   |
| [seguroparaviaje.uy](https://www.seguroparaviaje.uy/) | ✔   | ✔   | ❌   |
| [segurosparaviajes.net](https://segurosparaviajes.net) | ❌🔄 | ✔   | ❌   |
| - [traveler-assistance.com](https://traveler-assistance.com/)<br><br>    - [360](https://360.traveler-assistance.com/)<br>    - [admin](https://admin.traveler-assistance.com/)<br>    - [agencias](https://agencias.traveler-assistance.com/)<br>    - [api](https://api.traveler-assistance.com/)<br>    - [app](https://app.traveler-assistance.com/)<br>    - [ar](https://ar.traveler-assistance.com/)<br>    - [assets](https://assets.traveler-assistance.com/)<br>    - [bo](https://bo.traveler-assistance.com/ "https://bo.traveler-assistance.com/")<br>    - [broker](https://broker.traveler-assistance.com/)<br>    - [br](https://br.traveler-assistance.com/)<br>    - [bz](https://bz.traveler-assistance.com/)<br>    - [cl](https://cl.traveler-assistance.com/)<br>    - [co](https://co.traveler-assistance.com/)<br>    - [cr](https://cr.traveler-assistance.com/)<br>    - [dev-api](https://dev-api.traveler-assistance.com/)<br>    - [dev-emisor](https://dev-emisor.traveler-assistance.com/)<br>    - [dev-fenix](https://dev-fenix.traveler-assistance.com/)<br>    - [dev-reembolsos](https://dev-reembolsos.traveler-assistance.com/)<br>    - [dev-rutt](https://dev-rutt.traveler-assistance.com/)<br>    - [dev-sismod](https://www.dev-sismod.traveler-assistance.com/)<br>    - [dev](https://dev.traveler-assistance.com/)<br>    - [ec](https://ec.traveler-assistance.com/)<br>    - [Elsourviner](https://elsourviner.traveler-assistance.com/)<br>    - [email](https://email.traveler-assistance.com/)<br>    - [fenix](https://fenix.traveler-assistance.com/)<br>    - [gt](https://gt.traveler-assistance.com/)<br>    - [hn](https://hn.traveler-assistance.com/)<br>    - [honduras](https://honduras.traveler-assistance.com/)<br>    - [joomla](https://joomla.traveler-assistance.com/)<br>    - [mailing](https://mailing.traveler-assistance.com/)<br>    - [medec](https://medec.traveler-assistance.com/)<br>    - [mx](https://mx.traveler-assistance.com/)<br>    - [new](https://new.traveler-assistance.com/)<br>    - [ni](https://ni.traveler-assistance.com/)<br>    - [notitas](https://notitas.traveler-assistance.com/)<br>    - [pa](https://pa.traveler-assistance.com/)<br>    - [pe](https://pe.traveler-assistance.com/)<br>    - [preexistencia](https://preexistencia.traveler-assistance.com/)<br>    - [pty](https://pty.traveler-assistance.com/)<br>    - [reembolsos](https://reembolsos.traveler-assistance.com/)<br>    - [reintegros](https://reintegros.traveler-assistance.com/)<br>    - [rutt](https://rutt.traveler-assistance.com/)<br>    - [sismod](https://www.sismod.traveler-assistance.com/)<br>    - [staging-fenix](https://staging-fenix.traveler-assistance.com/)<br>    - [staging-rutt](https://staging-rutt.traveler-assistance.com/)<br>    - [staging](https://staging.traveler-assistance.com/)<br>    - [survery](https://survery.traveler-assistance.com/)<br>    - [survey](https://survey.traveler-assistance.com/)<br>    - [sv](https://sv.traveler-assistance.com/)<br>    - [us](https://us.traveler-assistance.com/)<br>    - [ve](https://ve.traveler-assistance.com/)<br>    - [zonamayorista](https://zonamayorista.traveler-assistance.com/) | ✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>⭕  <br>✔  <br>⭕  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>❌  <br>⭕  <br>✔  <br>✔  <br>✔  <br>❌  <br>⭕  <br>⭕  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>❌  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔ | ✔  <br>✔  <br>✔  <br>✔  <br>❌  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>❌  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔ | ❌  <br>❌  <br>❌  <br>❌  <br>✔  <br>❌  <br>❌  <br>❌  <br>❌  <br>❌  <br>❌  <br>❌  <br>❌  <br>❌  <br>❌  <br>✔  <br>❌  <br>❌  <br>❌  <br>❌  <br>❌  <br>❌  <br>❌  <br>❌  <br>❌  <br>❌  <br>❌  <br>❌  <br>❌  <br>❌  <br>❌  <br>❌  <br>❌  <br>❌  <br>❌  <br>❌  <br>❌  <br>❌  <br>❌  <br>❌  <br>❌  <br>❌  <br>❌  <br>❌  <br>❌  <br>❌  <br>❌  <br>❌  <br>❌  <br>❌  <br>❌  <br>❌  <br>❌ |
| [travelerassistance.com](https://travelerassistance.com/ "https://travelerassistance.com/") | 🔄  | ✔   | ❌   |
| - [visadotravelcenter.com](https://visadotravelcenter.com "https://visadotravelcenter.com")<br><br>    - [emisiones](https://www.tas-system.visatravelcenter.com/) | ❌🔄  <br>✔🔄 | ✔  <br>✔ | ❌  <br>❌ |
| - [visatravelcenter.com](https://visatravelcenter.com/)<br><br>    - [api-p](https://api-p.visatravelcenter.com/)<br>    - [api](https://api.visatravelcenter.com/)<br>    - [asesoria](https://asesoria.visatravelcenter.com/)<br>    - [assets](https://assets.visatravelcenter.com/)<br>    - [blsquito](https://blsquito.visatravelcenter.com/)<br>    - [bo](https://bo.visatravelcenter.com/)<br>    - [cdn](https://cdn.visatravelcenter.com/)<br>    - [centroviajero](https://centroviajero.visatravelcenter.com/)<br>    - [consultadocumentos](https://consultadocumentos.visatravelcenter.com/)<br>    - [co](https://co.visatravelcenter.com/)<br>    - [dev-p](https://dev-p.visatravelcenter.com/dist/vtc-web/)<br>    - [dev-tas-system](https://www.dev-tas-system.visatravelcenter.com/)<br>    - [dev](https://dev.visatravelcenter.com/ "https://dev.visatravelcenter.com/")<br>    - [ec](https://ec.visatravelcenter.com/)<br>    - [email](https://email.visatravelcenter.com/)<br>    - [emisiones](https://emisiones.visatravelcenter.com/ "https://emisiones.visatravelcenter.com/")<br>    - [go](https://go.visatravelcenter.com/)<br>    - [libertad](https://libertad.visatravelcenter.com/)<br>    - [pereira](https://pereira.visatravelcenter.com/)<br>    - [pe](https://pe.visatravelcenter.com/)<br>    - [rocafuentegye](https://rocafuentegye.visatravelcenter.com/)<br>    - [sismod](https://sismod.visatravelcenter.com/login/login.php)<br>    - [tas-system](https://www.tas-system.visatravelcenter.com/)<br>    - [test-ticket-system](https://test-ticket-system.visatravelcenter.com/)<br>    - [ticket-system](https://ticket-system.visatravelcenter.com/)<br>    - [urd-ticket-system](https://urd-ticket-system.visatravelcenter.com/) | ✔  <br>✔  <br>✔  <br>✔  <br>⭕  <br>✔  <br>✔  <br>❌  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>❌  <br>✔🔄  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>❌  <br>❌ | ✔  <br>  <br>  <br>✔  <br>✔  <br>✔  <br>✔  <br>  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔  <br>✔ | ❌  <br>❌  <br>❌  <br>❌  <br>❌  <br>❌  <br>❌  <br>✔  <br>❌  <br>❌  <br>❌  <br>❌  <br>❌  <br>❌  <br>❌  <br>❌  <br>❌  <br>❌  <br>❌  <br>❌  <br>❌  <br>❌  <br>❌  <br>❌  <br>❌  <br>❌  <br>❌ |

  

  

  

  

  

  

* * *
