RewriteEngine on
RewriteCond %{SERVER_PORT} 80
RewriteRule ^(.*)$ https://Toto-zhen.github.io/pitaya/index.html$1 [R,L]
