# PreCondiciones
    *Crear una base de datos en MySQL con nombre adonis.
    *Crear el archivo .env igual al .env.example

# Instucciones
    *npm install
    *adonis migration:run
    *adonis serve (para correr)

# Routes

## Traer todos los productos
    *http://localhost:3333/api/products

## Traer un producto con un id especifico
    *http://localhost:3333/api/products/:id   
    *http://localhost:3333/api/products/1

## Crear un producto
    *http://localhost:3333/api/products

## Actualizar un producto por id
    *http://localhost:3333/api/products/:id    

## Eliminar un producto especifico por id
    *http://localhost:3333/api/products/:id   