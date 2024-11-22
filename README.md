# Laboratorio-11-PW

Repo practica 11
Preguntas
1-R// en ese archivo se encuentran las configuraciones que tiene que tener para el arranque cuando se ponga en vercel
2-R// De que no hay que estar haciendo el deploy despues de cada commit, se hace automaticamente
3-R// El archivo vercel.json requiere tres propiedades principales para que una aplicación Express funcione correctamente: primero, "version": 2 que indica la versión de configuración de Vercel a utilizar; segundo, "builds" que especifica cómo construir la aplicación, donde debes incluir el archivo principal de tu app en "src", usar "@vercel/node" como builder y opcionalmente configurar "includeFiles" para incluir archivos específicos; y tercero, "routes" que define cómo se manejan las rutas en producción, típicamente usando "src": "/(.\*)" para capturar todas las rutas y "dest" para redirigirlas a tu archivo principal de Express.
