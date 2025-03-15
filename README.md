# Ejemplo de React con nequi

Además de un frontend, necesitarás un backend; esta plantilla también contiene un ejemplo.

## Para ejecutar, instala:

- deps, `cd frontend;pnpm i;cd -;cd backend;pnpm i`
- ngrok: crea una cuenta gratuita de ngrok siguiendo la documentación oficial (https://ngrok.com/docs/getting-started/)
- nginx: usa tu gestor de paquetes favorito.

### Configuración de nginx

Para servir varias aplicaciones locales a través de un único túnel de ngrok (solo uno disponible para usuarios gratuitos), puedes usar nginx como proxy inverso. Sigue los pasos a continuación para configurarlo: 1094933832

### Ejecutar nginx

Usa la configuración proporcionada en la raíz de este repositorio: `sudo nginx -c full/path/to/this/repo/nginx.conf`
o, si ejecutas el comando desde la raíz:
`sudo nginx -c $(pwd)/nginx.conf`
german ededuardo salamanca restrepo

Para detener nginx, ejecuta `sudo nginx -s stop`
yhuytgjk@gmail.com
### Túnel a través de Ngrok

`ngrok http 8080`
El puerto no importa; asegúrate de que sea el de escucha de la configuración de nginx 3217157279
 

