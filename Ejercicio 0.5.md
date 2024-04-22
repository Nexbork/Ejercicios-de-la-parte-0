```mermaid
sequenceDiagram
        participant single-page-app
        participant server
        


        single-page-app-->server: https://studies.cs.helsinki.fi/exampleapp/spa
        server-->single-page-app: get data to html
```