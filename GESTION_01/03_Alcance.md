# ALCANCE DEL PROYECTO SHOWROOM WEB

## 1. Proposito

Desarrollar una tienda de ropa ficticia como proyecto de portafolio para demostrar conocimientos de desarrollo frontend, backend, bases de datos, control de versiones, pruebas y documentacion.

## 2. Alcance incluido en el MVP

- Pagina de inicio y navegacion.
- Catalogo de productos.
- Visualizacion de detalles de cada producto.
- API REST desarrollada con Node.js y Express.
- Consulta de productos almacenados en MySQL.
- Carrito de compras con cantidades y calculo de subtotal.
- Validacion de entradas y manejo de errores.
- Diseno responsive.
- Consultas SQL parametrizadas.
- Configuracion de variables de entorno y proteccion de secretos.
- Pruebas funcionales basicas.
- Documentacion de instalacion y ejecucion.

## 3. Fuera del alcance inicial

- Cobros mediante pasarela de pagos real.
- Gestion avanzada de usuarios y roles.
- Panel administrativo completo.
- Integracion con empresas transportadoras.
- Envio automatico de correos.
- Cupones, reseñas y programas de fidelizacion.
- Analitica comercial avanzada.

Estas funciones podran incorporarse en versiones posteriores.

## 4. Criterios de aceptacion

- La aplicacion inicia siguiendo las instrucciones de instalacion.
- Los productos se obtienen desde el backend y la base de datos.
- El usuario puede consultar productos y sus detalles.
- El carrito permite agregar y quitar productos y modificar cantidades.
- Los totales se calculan correctamente.
- El servidor valida los datos relevantes y no confia en los precios enviados por el navegador.
- Las consultas a MySQL utilizan parametros.
- Los errores se gestionan sin exponer credenciales ni detalles internos sensibles.
- El diseno puede utilizarse en pantallas moviles y de escritorio.
- El repositorio contiene instrucciones de ejecucion y una lista de funciones implementadas y pendientes.

## 5. Limitaciones y supuestos

- La tienda utiliza una marca y datos ficticios.
- Se emplean productos de demostracion.
- El carrito no implica que exista un cobro real.
- Las funciones no implementadas se documentaran como pendientes.
- El alcance podra ajustarse segun el tiempo disponible.

## 6. Definicion de terminado

Una funcionalidad se considera terminada cuando esta implementada, probada, integrada, documentada y guardada en Git. Si no cumple todos estos criterios, se registra su estado real en Trello.