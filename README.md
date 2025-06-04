# Dokploy-Laravel-MySQL-PhpMyAdmin

Repositorio para crear con Dokploy contenedores de Laravel + MySQL + PhpMyAdmin. Usa el archivo 'dokploy.yaml' para crear todo. Usa el siguiente comando para iniciar todo:
```
dokploy up
```

### - **Acceso a los servicios**
Para cada entorno, puedes configurar variables en un archivo '.env':

**- Desarrollo:**
```
- Laravel: 'http://localhost'
- PhpMyAdmin: 'http://localhost:8080'
- MySQL: 'localhost:3306'
```

**- Producción:**
```
- Laravel: 'https://miapp.com'
- PhpMyAdmin: 'https://db.miapp.com'
- MySQL: 'mysql.miapp.com:3306'
```
