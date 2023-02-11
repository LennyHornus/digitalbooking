# digitalbooking
Proyecto Integrador CTD DH

## Indice
* [El Proyecto](#proyecto)
* [Equipo](#equipo)
* [Metodología de Trabajo](#metodología-de-trabajo)
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


