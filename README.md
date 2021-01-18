
```
version: '2'
services:
  mailjet-exporter:
    build: .
    ports:
      - 9187:9187
    environment:
      - BIND_PORT=9187
      - API_KEY_PRIVATE=YOUR_API_KEY_HERE
      - API_KEY_PUBLIC=YOUR_API_KEY_HERE
```
