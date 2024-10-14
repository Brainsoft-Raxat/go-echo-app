# Go Echo App

Simple Go web server using Echo framework.

## Build and Run

```bash
docker build -t go-echo-app .
docker run -p 8080:8080 go-echo-app
```

## Endpoints

- `/` - Returns "Hello, World!"
- `/health` - Health check endpoint, returns JSON `{ "status": "healthy"
