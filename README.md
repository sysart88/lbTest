



https://github.com/sysart88


http://pecl.php.net/package/memcache
$ cd extname
$ phpize
$ ./configure
$ make
# make install

--with-php-config=[Insert path to proper php-config here]

For example (my case):
./configure --with-php-config=/usr/local/php5/bin/php-config5
/Applications/XAMPP/xamppfiles/etc/php.ini

extension_dir = "/Applications/XAMPP/xamppfiles/lib/php/extensions/no-debug-non-zts-20131226/"
extension=memcache.so
