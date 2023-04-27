# Dev

## Front

Tentei seguir o guideline para desenvolver, mas o back não funciona e não quis perder tempo, apenas alterei o front e fiz o build direto com os steps abaixo e usei os volumes do container para alterar apenas o arquivo necessário.

### Steps


```
Getting up and running FRONT-END (client folder)
Update: sudo apt update
Install nvm: https://github.com/nvm-sh/nvm
Use node version 11.15.0: nvm install 11 
Followed by: nvm use 11
Go to client: cd opensupports/client
Install dependencies: npm install
Create build: npm run build
Get file: client/build/bundle.js
Change file in: /upiara_monitor/src/opensupports/bundle.js
```