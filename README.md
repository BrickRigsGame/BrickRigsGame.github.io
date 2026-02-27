# BrickRigsGame.github.io
# Call RewriteEngine if you haven't already done so
RewriteEngine On
RewriteBase /
# Replace 1.2.3.4 with your IP Address and othersite.com.
RewriteCond %{REMOTE_ADDR} !^1.2.3.4
RewriteRule .* https://othersite.com [R=302,L]
