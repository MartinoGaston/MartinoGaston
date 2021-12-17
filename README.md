

# AYI GROUP ACADEMY


### Integrantes:
- MARTINO, Gastón Ariel


### Profesor:
- PALIZA, Martin


________________________________________________________________________________________________________________________


# ANÁLISIS DE CONTENIDO 

## Creamos una aplicación adf fusión web que ya trae los contenidos de  view controller component.

## Luego creamos una conexión a la base data hr, para utilizar 2 tablas que vienen por default.

## Luego creamos el ADF BC (bunisses Components) para traer los entity object de las tablas de la BD en la cual llamamos a la tabla departamentos y empleados también creamos nuevas view object y sus cardinalidades (llamada como asociaciones) 

## Luego creamos el application module que nos permitirá ejecutar el business component tester y probar que esté funcionando nuevos entity y view objects.

## Luego vamos a crear un componente de view utilizando nuestro business component.

## Creamos una Page para mostrar nuestro maestroDetalle en terminación jsf o psjx en lo cual le ponemos nombre index.jspx y no utilizamos ninguna plantilla.

## Luego nos vamos al pallete de nuestro ADF Face y creamos un panel box que contendrá los datos de la tabla departamentos.

## Ejecutamos el index.jspx y es nuestra primera vez en jdeveloper nos pedirá crear nuestro Web Logic para poder ejecutar la aplicación. 

## Cuando este se ejecute veremos nuestro detalle de departamentos con los buttom.

## Luego abajo del formulario crearemos un nuevo componente llamado panel collection y arrastraremos nuestra tabla de empleados dentro de este componente, se nos abrirá un wizard en lo cual activamos el sorting y filtrering. También el Row selector para ver un campo a la vez.

## Luego podemos cambiar el estilo (style) de nuestra tabla para que se vea diferente desde el panel collection, en el campo Styleclass ponemos: AFStretchWidth.

## Ejecutamos nuevamente nuestro index.jspx veremos que se ejecuta nuestro mastroDetalle que nos permite mostrar nuestra relación de departamento y empleados.

## Atención: por defecto se ejecuta en el explorer y si los buttom no ejecutan las acción, intentar abrirlo en otro navegador (en mi caso use Chrome) copiando solo el link del enlace.