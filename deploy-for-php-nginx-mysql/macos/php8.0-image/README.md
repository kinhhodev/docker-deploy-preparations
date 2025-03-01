# Deploy PHP bằng Docker Compose
1. PHP 8.0 (**devilbox/php-fpm:8.0-slim-0.151**)
2. Mysql Server
3. Nginx
4. Certbot (optional)

## Chú thích về các folder

1. **workspace**: Folder chứa source code của bạn 

2. **nginx**: Folder chứa cấu hình nginx và logs (Hãy chỉnh sửa khi bạn có kinh nghiệm)
    + Biến môi trường: (chỉnh sửa ở file .env)
        1. NGINX_SERVER_NAME : Domain của bạn (Không gồm https:// hoặc http://). Nếu chạy ở máy tính cá nhân thì mặc định localhost

3. **mysql**: Folder chứa data của mysql server (không chỉnh sửa)
    + Biến môi trường: (chỉnh sửa ở file .env)
        1. MYSQL_DATABASE_NAME : Database của bạn
        2. MYSQL_ROOT_PASSWORD : Password của user root
        3. MYSQL_USER : Username của user mới
        4. MYSQL_PASSWORD : Password của user mới

4. **certbot**: Folder chứa data của certbot
    + Biến môi trường: (chỉnh sửa ở file .env)
        1. CERTBOT_EMAIL : Email để đăng ký SSL cho website

    > P/s: Certbot không hoạt động trên localhost
    
## Các gói/thư viện PHP support sẵn:
| Thư viện/Gói | Hỗ trợ |
|-------------|--------|
| amqp | ✅ |
| apcu | ✅ |
| bcmath | ✅ |
| bz2 | ✅ |
| calendar | ✅ |
| Core | ✅ |
| ctype | ✅ |
| curl | ✅ |
| date | ✅ |
| dba | ✅ |
| dom | ✅ |
| exif | ✅ |
| FFI | ✅ |
| fileinfo | ✅ |
| filter | ✅ |
| ftp | ✅ |
| gd | ✅ |
| gettext | ✅ |
| gmp | ✅ |
| hash | ✅ |
| iconv | ✅ |
| igbinary | ✅ |
| imagick | ✅ |
| imap | ✅ |
| intl | ✅ |
| json | ✅ |
| ldap | ✅ |
| libxml | ✅ |
| lz4 | ✅ |
| lzf | ✅ |
| mbstring | ✅ |
| mcrypt | ✅ |
| memcache | ✅ |
| memcached | ✅ |
| mongodb | ✅ |
| msgpack | ✅ |
| mysqli | ✅ |
| mysqlnd | ✅ |
| OAuth | ✅ |
| oci8 | ✅ |
| openssl | ✅ |
| pcntl | ✅ |
| pcre | ✅ |
| PDO | ✅ |
| pdo_dblib | ✅ |
| PDO_Firebird | ✅ |
| pdo_mysql | ✅ |
| PDO_OCI | ✅ |
| pdo_pgsql | ✅ |
| pdo_sqlite | ✅ |
| pdo_sqlsrv | ✅ |
| pgsql | ✅ |
| Phar | ✅ |
| posix | ✅ |
| pspell | ✅ |
| rdkafka | ✅ |
| readline | ✅ |
| redis | ✅ |
| Reflection | ✅ |
| session | ✅ |
| shmop | ✅ |
| SimpleXML | ✅ |
| snmp | ✅ |
| soap | ✅ |
| sockets | ✅ |
| sodium | ✅ |
| solr | ✅ |
| SPL | ✅ |
| sqlite3 | ✅ |
| sqlsrv | ✅ |
| ssh2 | ✅ |
| standard | ✅ |
| swoole | ✅ |
| sysvmsg | ✅ |
| sysvsem | ✅ |
| sysvshm | ✅ |
| tidy | ✅ |
| tokenizer | ✅ |
| uploadprogress | ✅ |
| uuid | ✅ |
| vips | ✅ |
| xdebug | ✅ |
| xlswriter | ✅ |
| xml | ✅ |
| xmlreader | ✅ |
| xmlrpc | ✅ |
| xmlwriter | ✅ |
| xsl | ✅ |
| yaml | ✅ |
| Zend OPcache | ✅ |
| zip | ✅ |
| zlib | ✅ |
| zstd | ✅ |