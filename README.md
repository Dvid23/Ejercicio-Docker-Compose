# Ejercicio-Docker-Compose
    Se levantaron 3 instancias de una API con build local, conectadas a PostgreSQL ademas usando Docker Compose

## Comandos
```bash
    docker compose up -d
```
## Configuración por entorno
```
    MESSAGE=<>
    POSTGRES_USER=<>
    POSTGRES_PASSWORD=<>
    POSTGRES_DB=<>
```
## Créditos
    - Cristian David Carranza Castillo
  
## Tipos de redes en Docker:


## Tipos de redes en Docker:
-   **Bridge**:Es una red privada que permite a los contenedores comunicarse entre sí.
-   **Host**:Es cuando se usa la misma red de la computadora sin aislamiento.
-   **None**:Es cuando el contenedor no tiene conexión de una red.
-   **Overlay**:Es cuando conectas contenedores que están en diferentes maquinas.
-   **Macvlan**:Le da al contenedor su propia dirección IP, como si fuera un dispositivo más a una red.

## Tipos de volúmenos en Docker:
-   **Named Volumes**:Crea un espacio de almacenamiento en algun lugar del Docker donde nosotros olo debemos colocar su nombre.
-   **Bind mounts**:Es cuando puedo elejir una carpeta de mi mismo computador se conecte o este en una carpeta en especifica del contenedor.
-   **Tmpts**:Los datos usados no se guardan sino ue solo estan temporamente en la memoria ram del contenedo, no son usadon solo si  se escesita algo rapido y temporal.