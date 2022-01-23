# EJEMPLO de Migracion- MYSQL-to-MongoDB

### ENLACE DEL NUEVO DISEÑO
![Imgur](KKK.png)


Este es un ejemplo probado de la migración de datos de MySQL a MongoDB en local.

También puede usar un host externo para migrar sus datos, que también se probó para funcionar correctamente.

### Method
Exportamos los datos consultados de la base de datos MySQL y luego insertamos los datos en la base de datos MongoDB

### 3. Database Setup

3-1 MySQL Database Connection Setup

Las variables básicas que necesita serían 'host', 'usuario', 'contraseña'. Para otras variables



3-2 MongoDB Connection Setup

Esta es una conexión de host local, puede cambiarla a otras conexiones externas, la URL podría ser como **`mongodb://USERNAME:PASSWORD@HOST:PORT/DATABASE`**.



### 5. Export then Import

Consultamos la tabla de MySQL, luego pasamos los resultados y los guardamos en la base de datos MongoDB.

