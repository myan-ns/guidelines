# Développer chez Naoned, un savoir-être

## Coder avec les standards

- Appliquez PSR-2 (http://www.php-fig.org/psr/psr-2/) Utilisez une extension à votre logiciel favori pour valider votre code à la volée (Pour Sublime 3 : Phpcs)
- Pas de tabulation, 4 espaces (2 pour le html et le twig)
- Tout en camel-case
- Faire de la revue de code (à definir)
- Écrire les tests en même temps que le code (à definir)
- Autre inspiration, les conventions de symfony : http://symfony.com/fr/doc/current/contributing/code/standards.html

## Git et le versionning

- Configurez Git : https://help.github.com/articles/set-up-git
- Ajoutez votre clé publique : https://help.github.com/articles/generating-ssh-keys
- Utilisez le modèle de «branchage» suivant décrit ici : http://nvie.com/posts/a-successful-git-branching-model/
- Faites des messages de commit explicite en anglais, sans être trop long, préfixé du numéro d’issue le cas échéant :
* ~~Fix a bug in discover~~
* ~~Remove event attached to body so the user can move the blocks as he saves and move them back again, issue 1880~~
* #1880 Fix discover block sort bug, due to crop events on body


## Rester au jus

- Soyez attentif aux bonnes pratiques − http://www.phptherightway.com est une bonne ressource
- Suviez l’actualité de vos domaines favori : twitter, flux rss …
- Assistez à des conférences, même en différé : https://www.youtube.com/user/afupPHP

## Humilité et respect

- Vous ferez du mauvais code
- Acceptez les critiques et les remarques
- Préferez l’**action** à la critique stérile
- Votre meilleure code d’aujourd’hui sera un boulet demain

## Ecrire du code pour les autres

- Vous lirez plus de code que vous n’en produirez
- Préférez être clair plutôt qu’être brèf
- Exposer uniquement ce qui est vraiment nécessaire et le faire explicitement (méthode privées)
- «La complexité n'a rien à voir avec l'intelligence, la simplicité, si."
- «Code toujours comme si le mec qui fait la maintenance est un psychopathe violent qui sait où tu habites.»
- Pendant la revue de code, essayez de deviner ce que les classes et les méthodes font juste par leurs noms, et vérifiez votre hypothèse. En cas d’erreur, proposez un meilleur nom.

## Communiquer clairement et sans retenue

- Mettez-vous dans la tête de votre interlocuteur
- Préférez les **discussions en chat ouverts** plutôt que privées
- Partagez chaque idée ou nouvelle orientation très tôt

## Soyez concret

- Mettre l'accent sur la prestation **pour le client**
- [YAGNI] (http://en.wikipedia.org/wiki/You_aren%27t_gonna_need_it) Écrivez votre code pour votre besoin **actuel et spécifique**
- Ne jamais écrire du code pour des raisons de «peut-être demain, vous en aurez besoin".
- [KISS] (http://en.wikipedia.org/wiki/KISS_principle)
- Ne pas utiliser des fonctions de programmation fantaisiste *juste parce que vous en êtes capable*. Utilisez les fonctions de programmation fantaisiste parce qu'ils ont un **avantage démontrable** spécifique pour le problème que vous essayez de résoudre.
- Toujours fournir un cas d'utilisation concret avec une spécification
- Savoir quand (ne pas) optimiser

## Concevoir le changement

- Dépendre des choses qui changent le moins souvent
- DRY − Programmer du code réutilisable
- Vous ne pouvez pas savoir *ce qui va changer*, mais vous pouvez être sûr que cela **va changer**.
- «Le design est plus l'art de conserver de la flexibilité que celui d'atteindre la perfection."

## Être responsable

- Estimez et planifiez avec précision, découpez en plus petites tâches si nécessaire.
- Prévoyez l'impact que votre code peut avoir sur l'environement
- Autant que possible, livrez les fonctionnalité finalisés et à temps, prévenir au plus tôt en cas de délai
- Toujours avoir l’**utilisateur final** à l'esprit

## Soyez vous-même

- Vous êtes ici pour une bonne raison :)
- Contribuez à une ambiance agréable

---
Inspirations and credits:

- https://signalvnoise.com/posts/3250-clarity-over-brevity-in-variable-and-method-names
- http://blog.codinghorror.com/kiss-and-yagni/
- http://www.articpost.com/best-programming-quotes-that-every-developer-should-know/
- https://github.com/iadvize/guidelines
