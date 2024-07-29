# library

cd frappe-bench

```bash
    bench start
```

# To change Admin password

```bash
    bench --site library.localhost set-admin-password library87
```

# To access your site

```bash
    http://library.localhost:8000
```

# access the python console

$ bench --site library.localhost console

# Access the mariadb console

$ bench --site library.localhost postgres

# Enable Developer Mode

$ bench set-config -g developer_mode true


$ bench set-config -g server_script_enabled true
