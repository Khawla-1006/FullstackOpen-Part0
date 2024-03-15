# this is a heading
<hr>

## 2nd heading
<hr>

*italic*

**bold text**

* list 
* list
* another list

>quote area

`<p>code goes here</p>
`

### Heading 3
---

```javascript
while(i< 10){
    text += "The number is" + i ;
    i++;
}
```



```mermaid
sequenceDiagram
    participant Client
    participant Server
    Client->>Server: Register user
    activate Server
    Server-->>Client: User already exists.
    deactivate Server

```
---

```mermaid
flowchart TD;
    A[start] --> B[process1]
    B --> C[process 2]
    C --> D[End]
```