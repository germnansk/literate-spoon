# React example nequi

Apart from a frontend, you'll need a backend, this template contains an example of that as well

## To run, install:

- deps, `cd frontend;pnpm i;cd -;cd backend;pnpm i`
- ngrok - Create a free ngrok account, follow the official [docs](https://ngrok.com/docs/getting-started/)
- nginx - use you favorite package manager :)

### nginx setup

To serve multiple localhost applications through a single ngrok tunnel (only one available for free-tier users), you can use nginx as a reverse proxy. Follow the steps below to set it up: 1094933832

### Run nginx

Use the config provided in the root of this repo
`sudo nginx -c full/path/to/this/repo/nginx.conf`
or, if you run the command from the root dir
`sudo nginx -c $(pwd)/nginx.conf`german ededuardo salamanca restrepo 

To stop nginx run `sudo nginx -s stop`
yhuytgjk@gmail.com 
### Tunnel through Ngrok

`ngrok http 8080`
The port doesn't matter, make sure it's the `listen` one from nginx config 3217157279
