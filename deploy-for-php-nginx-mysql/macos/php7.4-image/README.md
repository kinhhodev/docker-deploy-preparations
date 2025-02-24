# Deploy source php with following services
1. PHP 7.4 (**FROM devilbox/php-fpm:7.4-slim-0.151**)
2. mysql server
3. nginx
4. certbot (optional)

# Folder structure explain
1. workspace: mapping folder source in container 
    + Functional: folder source code
2. nginx: mapping folder /etc/nginx in container
    + Functional: folder contains config of nginx
    + Changes params: 
        - server_name
3. mysql: mapping folder 
    + Functional: folder contains mysql data

# PHP Packages Available:
| Package | Available |
|-------------|------------------------------------|
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