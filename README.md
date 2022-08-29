# Nginx Project

version: v0.3

## Usage

Docker Nginx Reverse Proxy

1. subdomain redirect to upstream.
2. proxy pass, load balance.
3. ssl on domain (backend can be secure too). (TODO)

## Start-up

### With Docker (& Docker compose)

- (sudo) docker network create web_service
- (sudo) docker compose up [-d]
- just have fun on domain and the upstream

## License

plz follow MIT License
