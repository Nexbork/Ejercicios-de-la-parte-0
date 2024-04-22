```mermaid
sequenceDiagram
        participant single-page-app
        participant server
        


        single-page-app-->server: https://studies.cs.helsinki.fi/exampleapp/spa
        server-->single-page-app: get data to html
        single-page-app-->server: user insert anything type of data and push save
        single-page-app-->server: server convert data to json
        single-page-app-->server: post https://studies.cs.helsinki.fi/new_note_spa
        server--> single-page-app: get data to new_note_spa with date on the console
        server--> single-page-app: get data to new_note_spa
```