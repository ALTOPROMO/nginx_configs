# Nginx configs v 0.1.0

## Структура

```text
nginx_configs/
├── pagespeed/          # Конфиги для модуля автоматицаии оптимизации работы сайта
│   ├── ps_off.conf     # Выключение - include nginx_configs/pagespeed/ps_off.conf
│   └── ps_on.conf      # Включение - include nginx_configs/pagespeed/ps_on.conf
├── php/                # Конфиги с php для apache2 и для php-fpm
│   ├── php.conf        # Включение apache_php
│   └── php-fpm.conf    # Включение php-fpm
└── local.conf          # Необходим кофиг для работы с сжатием и статикой
```