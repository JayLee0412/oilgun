
RewriteEngine on
RewriteCond %{SERVER_PORT} 80
RewriteRule ^(.*)$ https://JayLee0412.github.io/oilgun/index.html$1 [R,L]
