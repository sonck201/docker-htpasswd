# docker-htpasswd

## Usage

To generate a password file:

```zsh
docker run --rm -ti sonck201/docker-htpasswd-arm <username> <password>
```

This will use bcrypt encryption.
