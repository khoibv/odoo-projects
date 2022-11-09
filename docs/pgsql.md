## 1. Useful PostgreSQL CLI commands

### Login

    psql -U <username> <dbname>

### Show all CLI commands

    \?

### List all DB

    \l

### Switch to another DB

    \c <db-name>

### List objects in DB

(options: S = show system objects, + = additional detail)

```
\dt[S+] [PATTERN]      # list tables. For example: \dt email*
\dv[S+] [PATTERN]      # list views
\ds[S+] [PATTERN]      # list sequences
\dT[S+] [PATTERN]      # list data types
\du[S+] [PATTERN]      # list roles
\d[S+]                 # list tables, views, and sequences
```

## 2. Odoo commands

### List attachments

    SELECT * FROM ir_attachment;

### Show contraints in a module:
