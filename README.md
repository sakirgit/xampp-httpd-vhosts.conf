# xampp-httpd-vhosts.conf


File location : G:\xampp\apache\conf\extra

<VirtualHost *:80>
	DocumentRoot "G:\xampp\htdocs\path\of\dorectory"
	ServerName local-domain-name.local
	<Directory "G:\xampp\htdocs\path\of\dorectory">
		AllowOverride All
		Require all Granted
	</Directory>
</VirtualHost>



(Winsdows host file loadation: C:\Windows\System32\drivers\etc\host)
