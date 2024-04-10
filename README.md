# NodeJs, helloworld API for test propouses.

This is a simple API that returns a welcome message.

## Run your local environment

### Clone the repository
```bash
git clone https://github.com/juancarlosfunesmachicado/nodejs-helloworld-api.git
```

### Install dependencies
```bash
npm install
```

### Run the tests
```bash
npm test
```

### Start the server
```bash
npm start
```

### Make a request
```bash
curl http://localhost:3000
```

# GUIA DESAFIO 2

1. **Instalar Node VersionManager**
```bash
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.0/install.sh | bash

source ~/.bashrc

nvm install node
```
2. **Instalar y correr NGrok**
```bash
curl -s https://ngrok-agent.s3.amazonaws.com/ngrok.asc \
	| sudo tee /etc/apt/trusted.gpg.d/ngrok.asc >/dev/null \
	&& echo "deb https://ngrok-agent.s3.amazonaws.com buster main" \
	| sudo tee /etc/apt/sources.list.d/ngrok.list \
	&& sudo apt update \
	&& sudo apt install ngrok

ngrok config add-authtoken 2ersXkQX6PRgIuVZitSQqoVEkqL_43o56kwDyAKrfecx5x48P

ngrok http http://localhost:8080
```
3. **Clonar repositorio de Github**
```bash
git clone https://github.com/juancarlosfunesmachicado/nodejs-helloworld-api
```
4. **Configurar Github Webhook**
5. **Crear y configurar una tarea en Jenkins**
6. **Realizar Push en el repositoriio**
