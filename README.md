# digitalbooking
Proyecto Integrador CTD DH

## Indice
* [El Proyecto](#proyecto)
* [Equipo](#equipo)
* [Metodología de Trabajo](#metodología-de-trabajo)
* [Bitácora del Proyecto](#bitácora-del-proyecto)
* [Tecnologías Utilizadas](#tecnologías-utilizadas)
* [Documentación Técnica del Proyecto](#documentación-técnica-del-proyecto)
* [Documentación Técnica por Sprint](#documentación-técnica-por-sprint)


## El proyecto
Digital Booking es un sitio web que nos permite realizar reservas de alojamientos categorizados en hoteles, hostels, departamentos y bed & breakfast en distintos lugares turísticos del mundo.
El sitio puede ser utilizado por usuarios para buscar alojamientos y realizar reservas, y también por administradores, que además pueden publicar sus productos.

Nuestro objetivo es desarrollar un producto digital acorde a las funcionalidades requeridas por el cliente. Nuestra prioridad era lograr que sea responsivo, intuitivo y fácilmente de entender, para que los usuarios tengan una buena experiencia y vuelvan a visitarlo.
<br>
<br>

 ## Equipo 
**(Camada 1 - Equipo 3)**
<p>Los integrantes del equipo son:</p><br>
<div align="center"><em><h5>Lenny Hornus, Santiago Alvarez, Guido Ceriani, Ivanna Cingolani y Andres Robledo</h5></em></div>
<br>

---


## Metodología de trabajo

Trabajamos con Metodologías Ágiles. Para ello nos organizamos siguiendo las ceremonias de SCRUM (lectura y validación del sprint, daily, weekly, review, retro), modularizando el proyecto en 4 Sprints de 2 semanas cada uno.<br>
A lo largo del proyecto contamos con un Scrum Master, un Product Owner y el apoyo de diferentes Tech Leads en caso que necesitáramos realizar consultas técnicas. Utilizamos el Boards de GitLab como herramienta de organización y asignación de tareas y Metro Retro para asegurarnos de mejorar como equipo de manera progresiva para asi lograr los objetivos. 
Desde el comienzo del proyecto nos dividimos de manera clara los roles pero también establecimos solucionar en grupo aquellas dudas y features más complejas a resolver a lo largo del desarrollo.





## Tecnologías Utilizadas
<ul>

<li>Servicios & herramientas empleadas:
<ul>
<li>Gestión del proyecto: 
<ul> 
<li>GitLab Boards</li>  
<li>Gitlab Issues</li>  
<li>Metro Retro</li>
</ul>

</li>
<li>Desarrollo del proyecto: 
<ul> 
<li>IDEs
<ul> 
<li>Visual Studio Code</li>  
<li>IntelliJ</li>  
</ul>
</li>  
<li>Sistemas de Control de Versiones
<ul> 
<li>Git</li>
<li>Gitlab</li>  
</ul></li>  
</ul>
</ul>
</li>

<li>Tecnologías Utilizadas:
<ul> 
<li>Frontend
<ul> 
<li>Javascript</li>  
<li>React</li>  
<li>React-dates</li>  
<li>styled components</li>
<li>React alice carousel</li>  
</ul>
</li>  
<li>Backend
<ul> 
<li>Java</li>  
<li>Spring boot</li>  
<li>Swagger</li>
<li>JWT.io</li>
<li>Log4j</li>
<li>Lombok</li>
<li>JPA</li>  
</ul>
</li>  
<li>Base de Datos
<ul> 
<li>MySQL</li>  
<li>MySQLWorkbench</li>
<li>DBeaber</li>
<li>Flyway</li>  
</ul></li>  
<li>Testing
<ul> 
<li>Jest</li>  
<li>SeleniumIDE</li>  
<li>Postman</li>  
</ul></li>  
<li>Infraestructura
<ul>
<li> AWS
<ul> 
<li>Docker</li>  
<li>S3</li>  
<li>EC2</li>  
<li>RDS</li> 
<li>CI/CD</li> 
</ul>
</li>  
</ul>
</li> 
</ul>
</li>
</ul>

---
## Documentación Técnica del Proyecto

### Ambiente de Desarrollo

- **Setup**

Para comenzar a trabajar, clonar el repositorio de Gitlab: 

Con SSH: 
```
$ git clone https://github.com/LennyHornus/digitalbooking.git
```

Con HTTPS: 
```
$ git clone https://github.com/LennyHornus/digitalbooking.git
```

Para correr el proyecto, instale localmente las siguientes librerías:

```
$ cd ../proyecto/FrontEnd
$ npm install
$ npm start
```

- **Workflow**

[Link al Workflow](https://gl.deitech.online/ctd/proyecto-integrador-0522/0821-c1/grupo-03/-/network/development)
<br>
<p>El proyecto se lleva a cabo en la rama "main". De esta rama creamos la rama "development", donde ejecutamos los test correspondientes. De ella se desprenden ramas con cada feature que se encuentra en desarrollo (las mismas están detalladas en el board de "Issues"). Una vez realizada la feature, se mergea con la rama development haciendo un Pull Request (incluyendo un mensaje descriptivo sobre el contenido del pull request). Una vez realizados los test hacemos el merge de la rama development con la rama main</p>

---

- **Modelo Vista Controlador (MVC)**
<br>
![diseño-de-capas-web-api](uploads/6a28db222c493160cfe81980ae449217/diseño-de-capas-web-api.png)

---

- **Infraestructura**
<br>
![InfraAWS](uploads/99287b65db4d3e8ee87a0cd92b7d9186/InfraAWS.jpg)

---


## Documentación Técnica por Sprint

* [Sprint 1](#sprint-1) 
* [Sprint 2](#sprint-2) 
* [Sprint 3](#sprint-3)
* [Sprint 4](#sprint-4)

---

##  <div align="center"><strong>Sprint 1</strong></div>

### Base de Datos 
##### Diagrama Entidad-Relación de digitalbooking
<p>Creamos la base datos digitalbooking y la tabla "categories".</p>
<br>
 ![Sprint1](uploads/edcaaa43c6118b356b534a466c4e4d92/Sprint1.png)

---

### Componentes y Diagramas de la Aplicación

##### Documentación de la API

▫ [Link a la documentación de la API con Swagger](http://ec2-18-233-111-51.compute-1.amazonaws.com/swagger-ui/index.html)

---
### Infraestructura

##### Diagrama de Infraestructura
<br>
![InfraAWS](uploads/db94960c910ca3a06599d71f2bc94572/InfraAWS.jpg)

---

###  Testing

##### Casos de Prueba

 ▫ [Link a Casos de Prueba](https://docs.google.com/spreadsheets/d/1bfJzKTFHmY1OdETJ3Pa8pM62OVbm7vrM/edit#gid=78607399) 
<br>

##### Postman (Tests de API) 

Test Runner Results: 
![categoria](uploads/7194a9e59b62626ade9f4d1e629834cc/categoria.png)
---

### Tecnologías
En este sprint usamos: <br>

<ul> 
<li>Java</li>
<li>Spring boot</li>
<li>Log4J</li>
<li>Lombok</li>
<li>JPA</li>  
<li>MySQL</li>
<li>DBeaver</li>
<li>WorkBench</li>
<li>Flyway</li>  
<li>Postman</li>  
<li>React</li>
<li>React-dates</li>
<li>React alice carousel</li>
<li>Styled Components</li>
  
</ul>


---

##  <div align="center"><strong>Sprint 2</strong></div>

### Base de Datos
##### Diagrama Entidad-Relación de digitalbooking
<p>En este sprint creamos las tablas "products", "cities", "policy", "images" y "features". Establecimos las relaciones entre ellas y las mapeamos con la entidades de nuestro modelo mediante Spring JPA. </p>
<br>
![Sprint2](uploads/a893db71840bdf5e9d048132655aeeb5/Sprint2.png)

---

### Componentes y Diagramas de la Aplicación
##### Documentación de las APIs de Productos y Ciudades

▫ [Link a la documentación de la API con Swagger](http://ec2-18-233-111-51.compute-1.amazonaws.com/swagger-ui/index.html)

---

### Infraestructura

##### Diagrama de Infraestructura
<br>
![InfraAWS](uploads/fd6967d714e42a72e114109010d25a82/InfraAWS.jpg)

---

### Testing

##### Casos de Prueba

 ▫ [Link a Casos de Prueba](https://docs.google.com/spreadsheets/d/1bfJzKTFHmY1OdETJ3Pa8pM62OVbm7vrM/edit#gid=78607399) 
<br>
##### Jest

![jest](uploads/be014bcb20bc00cadd66364732da3936/jest.png)

##### Postman (Tests de APIs) 

Test runner results: 
![city](uploads/587246c251f17a3e1e667c0726f89639/city.png)

![feature](uploads/16cfb116dfe6a2cb642351ed728c0979/feature.png)

![image](uploads/5c6586d070f430ca7f63ef83b48ce36c/image.png)

![productypolicy](uploads/fa424fd129b3217ecc97095dac1955a2/productypolicy.png)
---

### Tecnologías
En este sprint usamos: <br>
<ul> 
<li>EC2</li>  
<li>S3</li>  
<li>RDS</li>  
<li>Jest</li>
<li>Selenium IDE</li>  
</ul>


[<div align= "right">![keyboard_arrow_up_FILL0_wght400_GRAD0_opsz48](uploads/25ad349b81af747887e5da348852592c/keyboard_arrow_up_FILL0_wght400_GRAD0_opsz48.png)</div>](#indice)

---

## <div align="center"><strong>Sprint 3</strong></div>

### Base de Datos
##### Diagrama Entidad-Relación de digitalbooking
<p>En este sprint creamos las tablas "reservation, "users", "roles" y "clients". Establecimos las relaciones entre ellas y las tablas existentes y las mapeamos con la entidades de nuestro modelo mediante Spring JPA. </p>
<br>
![Sprint3](uploads/68b7dcff3b0b1b821f1811f72abc2e17/Sprint3.png)

---

### Componentes y Diagramas de la Aplicación
##### Documentación de las APIs de Usuarios, Reservas.

▫ [Link a la documentación de la API con Swagger](http://ec2-18-233-111-51.compute-1.amazonaws.com/swagger-ui/index.html)

---

### Infraestructura

##### Diagrama de Infraestructura
<br>
![InfraAWS](uploads/79a58bcfd8f1707ce149a239b7fdfcdc/InfraAWS.jpg)

---

### Testing

##### Casos de Prueba

 ▫ [Link a Casos de Prueba](https://docs.google.com/spreadsheets/d/1bfJzKTFHmY1OdETJ3Pa8pM62OVbm7vrM/edit#gid=78607399) 
<br>
##### Jest

![jest](uploads/fd70acdd465f4e93392a1d132e725d6d/jest.png)

##### SeleniumIDE	

![SeleniumIDE](uploads/7a86df031059da19cb23b7e1a4d3b7b9/SeleniumIDE.png)

##### Postman (Tests de API) 

Test Runner Results:
![user](uploads/d962254bc0dd8ddf56b9cee7f5f9749f/user.png)
![reservation](uploads/015beed782194cd6cf25186e982af7a0/reservation.png)
---

### Tecnologías
En este sprint usamos: <br>

<ul> 
<li>Spring Security</li>  
<li>JWT</li>  
<li>JPQL</li>  
<li>CI/CD</li>
<li>Docker</li>  
</ul>


---

## <div align="center"><strong>Sprint 4</strong></div>
### Base de Datos
##### Diagrama Entidad-Relación de digitalbooking
<p>Creamos los filtros de reservas en base al id del usuario y creamos los endpoints del CRUD de productos.</p>
<br>
![BDdigitalbookingSprint4](uploads/526985a589de9d3dc02f6c306e6684bd/BDdigitalbookingSprint4.png)

---

### Componentes y Diagramas de la Aplicación
##### Documentación de las APIs de Usuarios, Reservas.

▫ [Link a la documentación de la API con Swagger](http://ec2-18-233-111-51.compute-1.amazonaws.com/swagger-ui/index.html)

---

### Infraestructura

##### Diagrama de Infraestructura
<br>
![InfraAWS](uploads/26de7c6f9c1163344ccf15b73a05630c/InfraAWS.jpg)

---

### Testing

##### Casos de Prueba

 ▫ [Link a Casos de Prueba](https://docs.google.com/spreadsheets/d/1bfJzKTFHmY1OdETJ3Pa8pM62OVbm7vrM/edit#gid=78607399) 
<br>
##### Jest

![jest](uploads/c63b299e2c8eb12a90533c741eba646e/jest.png)

##### SeleniumIDE	

![SeleniumIDE](uploads/437b6d5bede9526b1663cf51cbe08ed8/SeleniumIDE.png)

##### Postman (Tests de API)

Test Runner Results:
![user](uploads/66594fa1a66a02c2bd6a0fb0bd75edba/user.png)
![categoria](uploads/e7d777c20d23b34599be58843b702f5a/categoria.png)
![city](uploads/1546a419e0c6fdfb72a650eb6665e96d/city.png)
![feature](uploads/af71c4d08c6a9bc95b69996c08b09260/feature.png)
![image](uploads/79f8c9a0ba312f7fdd52ca775fbe880d/image.png)
![productypolicy](uploads/2a1ba62fbb1ff0aaf0109c92f2ffe4db/productypolicy.png)
![reservation](uploads/4e8b433808a31d2689b891294abb42e7/reservation.png)

##### Reporte final de Testing
▫ [Link a Reporte final de Testing](https://docs.google.com/document/d/1SfuRLzVw7AcsZ58fu3UfNwrcbvtcCz8z/edit?usp=sharing&ouid=107403431941075889636&rtpof=true&sd=true) 

---


---
