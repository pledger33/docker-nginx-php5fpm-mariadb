Installation complète sous docker de :

	- Nginx repo officiel

	- Installation de php5-fpm via un dockerfile, permettant de rajouter / supprimer des modules en fonction des besoins php

	- Installation de MariaDB


Les dossiers :

-	conf/nginx : Volume local pour la configuration personnalisée de nginx (default.conf) --> permet la configuration de l'interpretation de php et la communication avec le containeur php

-	conf/php : Volume local pour la configuration personnalisée de php5-fpm (www.conf) --> Permet la communication avec le containeur Nginx
