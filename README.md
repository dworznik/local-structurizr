
## C4 model

https://c4model.com

https://www.youtube.com/watch?v=Za1-v4Zkq5E

## Structurizr

https://structurizr.com

https://github.com/structurizr/lite


## Instalation

### Prerequisites

 - https://www.docker.com
 - https://docs.docker.com/compose/


```
npm install
npm run install-deps
```


## Editing and exporting diagrams

Choose the model to work on

```
export MODEL=BigBank
```


Run structurizr-lite in Docker

```
npm run start-server
```

Edit `BigBank/workspace.dsl` and go to http://localhost:8080/ to see the rendered diagrams


To export everything to `$MODEL/output` directory as PNG, run:

```
npm run export
```
