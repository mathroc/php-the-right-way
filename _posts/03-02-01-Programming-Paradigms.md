---
title: Concepts du langage
isChild: true
---

## Concepts du langage {#concepts_du_langage}

PHP est une langage souple et dynamique qui supporte des tenchiques de programmation variées. Il a évolué énormément au fil des années, introduisant notemment un modèle orienté objet complet dans PHP 5.0 (2004), les fonctions anonymes et les espaces de noms depuis PHP 5.3 (2009), et les "traits" depuis PHP 5.4 (2012). 

### Programmation orientée objet

PHP possède un panel de fonctionnalités orientées objet complet comprenant le support des classes, des classes abstraites, des interfaces, de l'héritage, des constructeurs, des exceptions, et plus.

* [Plus de détails sur la programmation orienté objet en PHP][oop]
* [Plus de détails sur les "Traits"][traits]

### Programmation procédurale

PHP  supporte les functions de première classe, ce qui signifie que l'on peux assigner une fonction à une variable. 
À la fois les fonctions définies par l'utilisateur et les fonctions pré-définies peuvent être assigné à des variables et 
invoquée dynamiquement. Les fonctions peuvent être passées comme arguments à d'autres fonctions (cette fonctionnalité est appelée fonction d'ordre supérieur) et les fonctions peuvent aussi renvoyer d'autres fonctions.

La récursivité est une fonctionnalité qui autorise une fonction à s'appeler elle même est également supportée par la langage mais la plupart du code PHP se concentre sur l'itération.

Les fonctions anonymes (avec le support des fermetures) sont disponible depuis PHP 5.3 (2009).

PHP 5.4 a ajouté la possibilité de lier une function anonyme à la portée d'un objet et a aussi amélioré le support des fonctions de rappel de sorte qu'il est maintenant possible de les utiliser de la même manière que les fonctions anonymes dans la plupart des cas..

* Poursuivre la lecture sur [la programmation fonctionelle en PHP](/pages/Functional-Programming.html)
* [Plus de détails sur les fonctions anonymes][anonymous-functions]
* [Plus de détails sur la classe `Closure`][closure-class]
* [Lire la RFC sur les closures][closures-rfc]
* [Plus de détails sur fonctions de rappels][callables]
* [Plus de détails sur l'appel dynamique des fonctions avec `call_user_func_array`][call-user-func-array]

### Méta programmation

PHP supporte différentes formes de méta programmation à travers des mécanismes tel que l'API de réflexion et les méthodes magiques. Il y a de nombreuse méthodes magiques disponible comme `__get()`, `__set()`, `__clone()`, `__toString()`, `__invoke()`, etc. qui permettent au développeurs de modifier le comportement d'une classe. Les développeurs Ruby disent souvent que PHP n'a pas l'équivalent de leur `method_missing`, mais on le trouve sous la forme de  `__call()` et `__callStatic()`.

* [Plus de détails sur les méthodes magiques][magic-methods]
* [Plus de détails sur la réflexion][reflection]

[namespaces]: http://www.php.net/manual/fr/language.namespaces.php
[overloading]: http://www.php.net/manual/fr/language.oop5.overloading.php
[oop]: http://www.php.net/manual/fr/language.oop5.php
[anonymous-functions]: http://www.php.net/manual/fr/functions.anonymous.php
[closure-class]: http://www.php.net/manual/fr/class.closure.php
[callables]: http://www.php.net/manual/fr/language.types.callable.php
[magic-methods]: http://www.php.net/manual/fr/language.oop5.magic.php
[reflection]: http://www.php.net/manual/fr/intro.reflection.php
[traits]: http://www.php.net/manual/fr/language.oop5.traits.php
[call-user-func-array]: http://www.php.net/manual/fr/function.call-user-func-array.php
[closures-rfc]: https://wiki.php.net/rfc/closures
