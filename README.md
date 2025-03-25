## wordpress-nginx-mysql
Docker Compose for a WordPress setup with Nginx and MySQL.
## **Installation**
To install Project Title, follow these steps:
1. Clone the repository: **`https://github.com/maestro6321/wordpress-nginx-mysql.git`**
2. Navigate to the project directory: **`cd project-title`**
> [!IMPORTANT]
>3.Create .env file (update passwords as needed):
>```bash
>DB_ROOT_PASSWORD=secure_root_pass
>DB_NAME=wordpress
>DB_USER=wp_user
>DB_PASSWORD=secure_db_pass
>```

> [!TIP]
> 4.Start the containers:
>```bash
> docker-compose up -d
>```
>5.Access WordPress in your browser at http://localhost

> [!WARNING]
> 1. Replace placeholder passwords in .env with secure ones.
> 2. Configure SSL/TLS for production use.
> 3. Set proper file permissions for the WordPress directory.
> 4. Regularly back up the **wordpress** directory and database volume.
> 5. Consider adding Redis/Memcached for object caching in production.
