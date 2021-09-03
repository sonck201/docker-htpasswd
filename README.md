# docker-htpasswd

## Usage

To generate a password file:

```zsh
docker run --rm -ti xmartlabs/htpasswd <username> <password>
```

This will use bcrypt encryption.
