```
    mermaid
    sequenceDiagram
        participant page-notes
        participant server
        


        page-notes-->server: https://studies.cs.helsinki.fi/exampleapp/notes
        server-->page-notes: get data to html
        page-notes-->server: user insert anything type of data and push save
        page-notes-->server: post https://studies.cs.helsinki.fi/exampleapp/new_note
        server--> page-notes: get data to new_note
```