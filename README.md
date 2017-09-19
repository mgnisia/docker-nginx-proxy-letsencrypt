# Docker Compose + Nginx Reverse Proxy + Let's Encrypt

## Usage

1. Edit your `docker-compose.yml` file to look like the one in the example folder: [docker-compose.yml](examples/django-gunicorn/docker-compose.yml)
2. Run your project's `docker-compose.yml`.
3. `git clone` or download this repository into your server.
4. Extract and/or `cd` to the cloned/downloaded path.
5. Run `docker-compose up -d`.

## Credits

- [@jwilder](https://github.com/jwilder/nginx-proxy)
- [@JrCs](https://github.com/JrCs/docker-letsencrypt-nginx-proxy-companion)
- [@evertramos](https://github.com/evertramos/docker-compose-letsencrypt-nginx-proxy-companion)
