```mermaid
flowchart TD
    start((printf_c)) --> getchar[read char from list   ]
    getchar --> printchar[print char]
    printchar --> returnchar[return 1]
```