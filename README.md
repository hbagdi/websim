# websim

Simulate web traffic 

## Building

### Mac/Linux

0) set GOROOT environment variable
1) Install Go and Make
2) make

### Docker

0) set GOROOT environment variable
1) Install Docker, Go and Make
2) make docker


## Running

### Mac/Linux

```
./websim
```

### Docker

```
docker pull maguec/websim:latest
docker run -i -t -p 8080:8080 maguec/websim
```

## Testing

run either the docker container or the raw application binary

```
curl http://localhost:8080/health
```

---
Copyright © 2018, Chris Mague
