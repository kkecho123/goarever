# Go Reverse Proxy

A lightweight reverse proxy library for Go applications.

## Features

- HTTP/HTTPS support
- WebSocket proxying
- Load balancing
- Health checks

## Installation

```bash
go get github.com/kkecho123/goarever
```

## Usage

```go
import "github.com/kkecho123/goarever/proxy"

func main() {
    p := proxy.New()
    p.AddBackend("http://localhost:8080")
    p.ListenAndServe(":80")
}
```

## License

MIT
