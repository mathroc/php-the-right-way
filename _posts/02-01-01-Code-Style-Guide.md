---
title: Convention d'écriture
---

# Convention d'écriture  {#convention_d'écriture}

La communauté PHP est largé et diversifié, composé d'innombrable librairies, frameworks, and composants. Il est commune
pour les développeurs PHP d'en choisirs plusieurs et de les combiner au sein d'un même projet. Il est important que 
le code PHP adhère (autant que faire se peut) à une convention d'écriture commune afin de simplifier aux développeurs
le mélange et le rapprochement de des différentes libraries dans leurs projets.

Le [Framework Interop Group][fig] a proposé et validé une séries de recommendations d'écriture, appelées [PSR-0][psr0], [PSR-1][psr1] et [PSR-2][psr2]. Ne laissez pas ces noms étranges vous dérouter, ces recommendations sont simplement un ensemble de reègles que des projets tel que Drupal, Zend, Symfony, CakePHP, phpBB, AWS SDK, FuelPHP, Lithium, etc. commencent à adopter. Vous pouvez les utiliser pour vos propres projets ou vous pouvez continuer à coder selon vos propres conventions.

Idéalement, vous devriez écrire du code PHP qui adhère à un standard connu: une ou plusieurs des recommendation PSR, ou un des standards émit par PEAR ou Zend. Cela permet aux autres développeurs de pouvoir facilement lire et 
travailler avec votre code, et les applications qui utilisent d'autres composants peuvent rester homogène même 
en utilisant beaucoup de code externe. 

* [Plus de détails sur PSR-0][psr0]
* [Plus de détails sur PSR-1][psr1]
* [Plus de détails sur PSR-2][psr2]
* [Plus de détails sur le standards d'écriture PEAR][pear-cs]
* [Plus de détails sur le standards d'écriture Zend][zend-cs]

Vous pouvez utiliser [PHP_CodeSniffer][phpcs] tester du code selon une des conventions, il existe aussi des plugins pour 
les éditeurs de texte tel que [Sublime Text][st-cs] pour être prévenus en temps réel. 

Utilisez le [PHP Coding Standards Fixer][phpcsfixer] de Fabien Potencier pour automatiquement modifier votre code pour 
qu'il respecte ces standards, vous épargnant de corriger manuellement chaque problème.

L'Anglais et la langue préférée pour tous les nom de symboles et l'infrastructure du code. Les commentaires peuvent être écrit dans n'importe quelle langue lue facilement par tous les contributeurs présent et futur.

[fig]: http://www.php-fig.org/
[psr0]: https://github.com/php-fig/fig-standards/blob/master/accepted/fr/PSR-0.md
[psr1]: https://github.com/php-fig/fig-standards/blob/master/accepted/fr/PSR-1-basic-coding-standard.md
[psr2]: https://github.com/php-fig/fig-standards/blob/master/accepted/fr/PSR-2-coding-style-guide.md
[pear-cs]: http://pear.php.net/manual/en/standards.php
[zend-cs]: http://framework.zend.com/wiki/display/ZFDEV2/Coding+Standards
[phpcs]: http://pear.php.net/package/PHP_CodeSniffer/
[st-cs]: https://github.com/benmatselby/sublime-phpcs
[phpcsfixer]: http://cs.sensiolabs.org/
