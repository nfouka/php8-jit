# PHP 8 -jit Just IN Time Builder
MandelBrot for PHP8 VS PHP7.x



# Build with JIT 
/usr/bin/php7.4 -dopcache.enable_cli=1 -dopcache.jit_buffer_size=100 bench.php <br/>
/usr/bin/php7.3 -dopcache.enable_cli=1 -dopcache.jit_buffer_size=100 bench.php <br/>
/usr/bin/php7.2 -dopcache.enable_cli=1 -dopcache.jit_buffer_size=100 bench.php <br/>
/usr/bin/php7.1 -dopcache.enable_cli=1 -dopcache.jit_buffer_size=100 bench.php <br/>
/usr/bin/php8.0 -dopcache.enable_cli=1 -dopcache.jit_buffer_size=100 bench.php <br/>

