# addres_book
-
A simple book aplication to store  and manage contact information

## Link 
- Url Deployment  :
- Repository :

## Features 

- Add,edit and delete contacts
- search contact by name  or email 

## Tech Stack 
- Html
- Css
- JavaScript

 ## Flowchart

```mermaid
flowchart TD
    A[Start] --> B[Display Contact List]
    B --> C{User Action}
    C -->|Add Contact| D[Show Add Contact Form]
    C -->|Edit Contact| E[Show Edit Contact Form]
    C -->|Delete Contact| F[Confirm Deletion]
    D --> G[Save New Contact]
    E --> H[Update Contact]
    F --> I[Remove Contact]
    G --> B
    H --> B
    I --> B
    B --> J[End]
```
