# Full Stack Open

My Full Stack Open course exercises and projects.

## Part 0: Fundamentals of Web Apps

### 0.4: New note diagram

```mermaid
sequenceDiagram
    participant browser
    participant server
    browser->>server: POST /exampleapp/new_note
    server-->>browser: 302 Redirect to /exampleapp/notes
    browser->>server: GET /exampleapp/notes
    server-->>browser: HTML document
