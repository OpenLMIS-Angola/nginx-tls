# nginx-tls

## Logging
By default, Nginx logs are stored under `/var/log/nginx` directory folder. The directory is marked as VOLUME and can be mounted to, in order to retrieve logging data. Additionally, user can specify different directories for logging, using `NGINX_LOG_DIR` environment variable.

## Configurable environment variables:<a name="env-variables"></a>
##### `VIRTUAL_HOST`
Name of the server host. It has no default value and must be provided.
##### `NGINX_REVERSE_PROXY`
An address of the service which handles reverse proxy e.g. `development.country.openlmis.org` or `123.456.789.123`.


