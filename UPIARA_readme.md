# Dev

## Front

Tentei seguir o guideline para desenvolver, mas o back não funciona e não quis perder tempo, apenas alterei o front e fiz o build direto com os steps abaixo e usei os volumes do container para alterar apenas o arquivo necessário.

### Setup

    Go to client: cd opensupports/client
    Install nvm: https://github.com/nvm-sh/nvm

```
nvm install 11 
nvm use 11
npm install
```

### Start

```
npm run serve
```

### Build

```
Create build: npm run build
```

    Get file: client/build/bundle.js
    Change file in: /upiara_monitor/src/opensupports/bundle.js
