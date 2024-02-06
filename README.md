# test in codespace

## test odoo 15
cd 15.0
docker compose up

## test odoo 16
cd 16.0
docker compose up

## test odoo 17
cd 17.0
docker compose up

## test odoo 16, homesumana version

cd homesumana
docker build -t homesumana/odoo-docker:16 .
docker compose up
