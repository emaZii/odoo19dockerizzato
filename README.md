### comandi per risolvere problemi 

## per creagli il db che non lo crea in automatico: "KeyError: 'ir.http'"
docker exec -it odoo19_app odoo -d lab19 --init=base --stop-after-init
