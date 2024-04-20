# test in codespace

## test odoo 17
cd ce/17.0\
docker compose up

## test odoo 17, homesumana version

cd ce-homesumana/17.0\
docker build -t homesumana/odoo-docker:17 .\
docker compose up

## test odoo 17 Enterprise, homesumana version

cd ee-homesumana/ee-src\
tar -xvzf ../../ee/wattana_psnsoft/odoo_17.0+e.latest.tar.gz

cd ee-homesumana/17.0\
docker build -t homesumana/odoo-docker:17 .\
docker compose up
