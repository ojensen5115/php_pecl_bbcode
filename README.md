# php_pecl_bbcode
PHP PECL BBCode rewrite to PHP7

To build and install:

    apt install php-dev
    phpize
    ./configure
    make
    sudo make install

Then to enable, add `extension=bbcode.so` to `php.ini`, and `systemctl restart apache2`
