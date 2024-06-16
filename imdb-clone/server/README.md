# How to run the server locally?
-1. Install golang
https://go.dev/doc/install

0. Run the PostgresSQL instance

```bash
docker-compose up -d
```

1. Install the dependencies

```bash
go mod download
```

2. Run the server

```bash
go run ./cmd/api
```
