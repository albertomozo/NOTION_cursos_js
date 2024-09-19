# Aplicación conectada a NOTION

Ejemplos de codigo en Javascript para usar la API de Notion. Son los ejercicos de la presentación Notion-Developer https://docs.google.com/presentation/d/1v1USzbwEwoH0-Iz-hUi6vXPtWIH9meBNFXwxdlacf78/edit?usp=sharing



## index.html

Ppágina de incio, que enlaza con todas las paginas posteriore

## 01-formu_usuario.html

Página en la que integro un forulario realizo con Noteform

## 02-json.html

Usando el codigo que nos sumnistra POSTMAN, tenemos el problema de CORS. NOTION Bloquea  los accesos en los que se envian autentificaciones desde el cliente. La solución es instalar node.js con express y usar JS como lenguaje de servidor.

## 03-json.html

Para evitar  CORS, copiamos el contenido de la respuesta (JSON) y lo asignamos a una variable cursos. Ir a la consola y analizar la variable cursos.

## 04-listacursos.html

Usando la variable del ejercicio anterior, presentamos la información  de los titulos de los cursos.

## EJERCICIOS PROPUESTOS 🧾

Obtener en cada linea, el enlace al documento y la categoria 

