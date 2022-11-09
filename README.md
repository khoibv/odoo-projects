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
