---
isChild: true
---

## Vagrant {#vagrant}

Exécuter votre application dans différents environnement pendant le développement et en production peut faire 
ressortir d'étranges bugs après un déploiement. De même lorsque l'on travaille en équipe, il n'est pas évident de 
maintenir à jour les environnements de développement avec les mêmes versions de librairies. 

Si vous développez sur Windows et déployez sur Linux (ou quoique ce soit d'autre que Windows) ou si vous travaillez
dans une équipe, vous devriez envisager d'utiliser une machine virtuelle. Ça semble complèxe, mais avec [Vagrant][vagrant] 
vous pouvez installer une machine virtuelle simple en seulement quelques étapes. Ces machines virtuelles basique 
peuvent être configuré manuellement, ou des outils de "provisioning" tel que [Puppet][puppet] ou [Chef][chef] peuvent
faire ceci pour vous. Provisionner la machine virtuelle est une bonne façon d'être certain que toutes les mahcines 
virtuelles sont configurées de manière identique et vous décharge du besoin de maintenir des listes de commandes complèxes
de configuration. Vous pouvez aussi détruire ("destroy") une machine virtuelle et la recréer sans aucune intervention manuelle, rendant trivial le processus de création d'une installation "fraîche".

Vagrant crée des dossiers partagés afin de rendre votre code accéssible à la fois par votre machine hôte et par la machine 
virtuelle, cela signifie que vous pouvez créer et modifier les fichiers sur votre machine hôte et exécuter le code dans la 
machine virtuelle.

### Un peu d'aide

Si vous avez besoin d'un peu d'aitre pour commencer à utiliser Vagrant, voilà deux services qui peuvent être utile:

- [Rove][rove]: service qui permet de générer des fichiers de configuration Vagrant pour des besoins standards, PHP entre autres. Le
  provisionnement est fait avec Chef.
- [Puphpet][puphpet]: interface permettant de configurer une machine virtuelle pour développer avec PHP development. **très orrienté PHP**. De plus, les machines virtuelles locales peuvent être utilisé pour être déployées vers des services "cloud". Le provisionnement est fait avec Puppet.

[vagrant]: http://vagrantup.com/
[puppet]: http://www.puppetlabs.com/
[chef]: http://www.opscode.com/
[rove]: http://rove.io/
[puphpet]: https://puphpet.com/
