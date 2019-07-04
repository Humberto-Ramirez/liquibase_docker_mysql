# liquibase_docker_mysql
Initial setup for liquibase 3.6.3, docker and mysql


## Consideraciones
 + Gradle 
    > Versión:
   `5.4.1`
   
   
## build docker container

> gradle startContainer


## liquibase update

> gradle update


### Configuración Inicial
 
 + Build Docker & Gradle Update    
     
    > `./run.sh` Creación del contenedor de la base de datos y aplicación de los cambios sobre la bd.
 
 + Parámetros de conexión
    ```
        database: utilsDb
        user: DkrUserDb
        pass: PswDkrDev#
        root-pwd: RootPswDev#
        port: 3406
    ```  
    
 ### Autores
  - Humberto Ramírez
  
 
## Licencia
 Este proyecto esta bajo la licencia...
