# Part0

## Exercise0.6

*Creating a new note using Single page app*
---

```mermaid
flowchart TD
A[New note] --> a[Submit]
a --> C[Server]
C --> |Fetch JavaScript Code|c[Executing Javascript Code]
c --> |JSON data|d[DOM API]
d --> D[Adding HTML elements for displaying the notes]
D --> |Redirect|E[Reload the notes]
```