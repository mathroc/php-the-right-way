---
title: Installation sur Windows
isChild: true
---

## Installation sur Windows {#installation_sur_windows}

PHP est disponible installable de plusieurs façon sur Windows. Vous pouvez [télécharger les exécutables][php-downloads] et jusqu'à récement on pouvait utiliser un installeur '.msi'. L'installeur n'est plus supporté et s'arrête à PHP 5.3.0.

Pour l'apprentissage et le développement en local, vous pouvez utiliser le serveur web interne avec PHP 5.4+ qui ne nécéssite pas de configuration. Si vous voulez un ensemble "tout-en-un" qui inclut aussi un serveur web complet et MySQL dans ce cas, des outils tel que [Microsfot Web Platform][wpi], 
[Zend Serveur CE][zsce], [XAMPP][xampp] et [WAMP][wamp] vont vous permettre de mettre en place rapidement un environnement de développement complet. Ceci étant dit, ces outils seront un peu différent des outils de production; soyez dont prudent aux différences d'environnment si vous travaillez sur Windows et déployez sur Linux.

Se vous devez faire tourner votre système de production sur Windows alors IIS7 vous offrira la plus grande stabilité et la meilleure performance. Vous pouvez utiliser
[PHP Manager][phpmanager] (un plugin pour IIS7) pour rendre simple la configuration et la gestion de PHP. IIS7 vient avec FastCGI installé et prêt à utiliser, vous devez juste configurer PHP comme gestionnaire. Vous trouverez de l'assistance et des ressources complémentaires sur la [zone dédiée à PHP sur iis.net][php-iis].
PHP.

[php-downloads]: http://windows.php.net
[phpmanager]: http://phpmanager.codeplex.com/
[wpi]: http://www.microsoft.com/web/downloads/platform.aspx
[zsce]: http://www.zend.com/fr/products/server/free-edition
[xampp]: http://www.apachefriends.org/fr/xampp.html
[wamp]: http://www.wampserver.com/
[php-iis]: http://php.iis.net/
