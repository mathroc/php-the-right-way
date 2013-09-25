---
title: Espaces de noms
isChild: true
---

## Espaces de noms {#espaces_de_noms}

Comme mentionné précédement, la communauté PHP a beaucoup de développeurs produisant une grande quantité 
de code. Cela signifie que le code d'une librairie PHP peut utiliser le même nom de classe qu'une autre librairie. Lorsque 
ces deux libraries sont utilisé dans le même espace de noms, elles entrent en conflit et créent des problèmes.

Les _espaces de noms_ résolvent ce problème. Comme expliqué dans le manuel PHP, les espaces de noms peuvent être 
comparés aux dossiers du système d'exploitation : deux fichiers avec le même nom peuvent coexister dans deux dossiers distincts. De la même façon, deux classes PHP avec le même nom peuvent coexister dans des espaces de noms PHP distincts. C'est aussi simple que cela.

Il est important que vous placiez vos classes dans un espace de noms dans votre code afin qu'il puisse être utilisé par 
d'autres développeurs sans craindre de entrer en conflit avec d'autres libraries

Une façon recommandées d'utiliser les espaces de nomes est décrite dans [PSR-0][psr0], qui a pour but de donner 
une convention de nommage standard pour les fichiers, classes et espaces de noms pour permettre la réutilisation de code.

* [Plus de détails sur les espaces de noms][namespaces]
* [Plus de détails sur PSR-0][psr0]

[namespaces]: http://www.php.net/manual/fr/language.namespaces.php
[psr0]: https://github.com/php-fig/fig-standards/blob/master/accepted/fr/PSR-0.md
