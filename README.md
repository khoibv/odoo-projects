# Odoo versions with Docker

---

## Copy and rename files:

```
.env.example            => .env         (+ change version of Odoo if need)
odoo.conf.example       => odoo.conf    (+ update configuration if need)
odoo_pg_pass.example    => odoo_pg_pass (+ update password postgresql)
```

## Start docker

```
docker-compose up -d
```

## Access to Odoo

|Version|Web URL|DB connection
|-|-|-|
|17|http://localhost:17069|localhost:17432@odoo:password
|16|http://localhost:16069|localhost:16432@odoo:password
|15|http://localhost:15069|localhost:15432@odoo:password
|14|http://localhost:14069|localhost:14432@odoo:password
|13|http://localhost:13069|localhost:13432@odoo:password
|12|http://localhost:12069|localhost:12432@odoo:password
|11|http://localhost:11069|localhost:11432@odoo:password

*Note: DB password is stored in `odoo_pg_pass` file*

