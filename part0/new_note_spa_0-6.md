Sequence Diagram depicting the situation where the user creates a new note on the page https://studies.cs.helsinki.fi/exampleapp/spa


```mermaid
sequenceDiagram
    participant browser
    participant server

    browser->>server: POST https://studies.cs.helsinki.fi/exampleapp/new_note
    activate server
    server->>browser: 201 Created
    deactivate server

```