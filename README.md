# CouchDB-ejemplo / Viveros Blanco
# Instalación y Configuración de CouchDB

Este documento describe el proceso de instalación y configuración de CouchDB en un sistema operativo Windows.

## 1. Descargar e Instalar CouchDB

### Descripción
Visita el sitio oficial de Apache CouchDB y descarga la versión más reciente para Windows.

### Pasos a seguir:
1. **Visita el sitio oficial**: Dirígete a [Apache CouchDB](http://couchdb.apache.org/) para obtener la última versión.
2. **Descarga el instalador**: Selecciona el instalador correspondiente a tu sistema operativo (Windows).
3. **Ejecuta el instalador**: Haz doble clic en el archivo descargado y sigue las instrucciones en pantalla para completar la instalación.

## 2. Iniciar CouchDB

### Descripción
Inicia CouchDB utilizando el acceso directo "Start CouchDB" en el menú Inicio.

### Pasos a seguir:
1. Busca el acceso directo "Start CouchDB" en tu menú Inicio.
2. Al iniciarlo, deberías ver un mensaje indicando que CouchDB ha comenzado en `http://127.0.0.1:5984/`.

## 3. Verificar la Instalación

### Descripción
Abre un navegador web e ingresa la URL `http://127.0.0.1:5984/` para verificar que CouchDB está funcionando.

### Pasos a seguir:
1. Abre tu navegador y escribe `http://127.0.0.1:5984/`.
2. Deberías ver una respuesta JSON confirmando que CouchDB está operativo.

## 4. Acceder a Futon (Interfaz Web)

### Descripción
Accede a la interfaz administrativa (Futon) ingresando `http://127.0.0.1:5984/_utils` en el navegador.

### Pasos a seguir:
1. En tu navegador, ingresa `http://127.0.0.1:5984/_utils`.
2. La interfaz se cargará permitiéndote gestionar bases de datos y documentos.

## 5. Crear una Nueva Base de Datos

### Descripción
En Futon, puedes crear una nueva base de datos.

### Pasos a seguir:
1. Haz clic en "Create Database".
2. Introduce el nombre deseado para tu base de datos (por ejemplo, `mis_datos`) y haz clic en "Create".

## 6. Agregar Documentos a la Base de Datos

### Descripción
Puedes agregar documentos a la base de datos utilizando Futon.

### Pasos a seguir:
1. Selecciona tu base de datos recién creada.
2. Haz clic en "Create Document".
3. Introduce los campos deseados en formato JSON


### Instrucciones para Usar el Código:

1. **Guardar el Archivo**: Guarda este contenido en un archivo llamado `README.md` en la raíz de tu repositorio.
2. **Subir a GitHub**: Si no lo has hecho ya, sube tu repositorio a GitHub para que otros puedan ver tu documentación.
