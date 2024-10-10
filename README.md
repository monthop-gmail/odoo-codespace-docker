# test in codespace

## test odoo 18
cd ce/18.0\
docker compose up

## test odoo 18, homesumana version

cd ce-homesumana/18.0\
docker build -t homesumana/odoo-docker:18 .\
docker compose up

## test odoo 18 Enterprise, homesumana version

cd ee-homesumana/ee-src\
tar -xvzf ../../ee/wattana_psnsoft/odoo_18.0+e.latest.tar.gz

cd ee-homesumana/18.0\
docker build -t homesumana/odoo-docker:18 .\
docker compose up
