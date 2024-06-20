# odoo-traefik-docker
Quick start for odoo websites running with postgres and traefik using docker compose.
This is currently built with Odoo 16 and Postgres 15 and Traefik 2.10.
However, all three docker packages have available major version updates that will require revision of this docker compose file.

## You will need to replace the following variables:

### {CF ACCOUNT EMAIL ADDRESS} = example_email@example_domain.com
### {CF API TOKEN} = Cloudflare API Token
### {DOMAIN NAME} = your_domain.com
### {odoo database password} = odoo database password, use during odoo initial setup to connect to postgres database
