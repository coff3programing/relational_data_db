# Files API

## Metodologias **(EC)**

- METODOLOGIA_ID INT SERIAL AUTOINCREMENT
- METODOLOGIA_NOMBRE VARCHAR(50)

## ARCHIVOS **(ED)**

- ARCHIVO_ID INT SERIAL AUTOINCREMENT
- METODOLOGIA_ID INT **(FK)**
- N_SUBDIVICION INT
- NOMBRE_ARCHIVO TEXT
- FECHA_ARCHIVO DATETIME

## Relaciones

- Una metodologia puede pertenecer a muchos archivos **(1 a N)**

## Operaciones

- Una metodologia puede ser creada
- Una metodologia puede ser leida

- Un archivo puede almacenar datos
- Un archivo puede ser leido
- Un archivo puede ser accedido mediante el nombre
- Un archivo puede ser eliminado

## Img

![First App Img](../img/firstapi.drawio.png)
