# prestashop-debug
Debug Prestashop with XDebug

## Usage

Git clone the repo, cd to the directory and then:

`docker compose up -d`

## Troubleshoot

If you get an error in the post-installation script, go to the terminal of the server in Docker and enter the following command:

```bash
cd /var/www/html
mkdir admin-dev
chown -R www-data:www-data admin-dev
chmod -R 755 admin-dev
```
