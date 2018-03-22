---
category: Divers
description: Memba a choisi nodeJS, expressJS, mongoDB et phonegap pour construire ses solutions logicielles.
icon: leaf
keywords: Memba, Kidoju, Microsoft, Visual, Basic, C++, J++, C#, Studio, Silverlight, Java, MTS, SQL, MySQL, Oracle, logiciel libre, informatique dématérialisée, Amazon, AWS, Apple, iOS, Android, JavaScript, nodeJS, MEAN
language: fr
title: Phonegap et l'architecture MEAN
uuid: 5265f6d7-ba3d-41e0-be8a-fee45caa501c
author: jlchereau
author_url: https://github.com/jlchereau
avatar_url: https://avatars.githubusercontent.com/u/2556751?v=3
creation_date: 2014-12-23T09:11:34Z
edit_url: https://github.com/Memba/www.memba.com/blob/master/fr/posts/2014/mean.md
site_url: https://www.memba.com/fr/posts/2014/12/mean
---
### Il n’y a pas si longtemps

Memba a longtemps été une boutique Microsoft et nous étions même Microsoft ISV et partenaire Microsoft. 
Notre équipe de développement avec l’expérience de Visual Basic, Visual C++, Visual J++ et Visual Studio .NET, y inclus C#.

Comme la plupart des gourous de l’orienté-objet, nous n’avons jamais été de grands enthousiastes de HTML. Nous avions aussi le sentiment profond que le mélange de langages et d’architectures des applications web pouvait être simplifié, outre la frustration de travailler avec des boites noires.
 
### Les blocs MEAN

![Les blocs MEAN](https://raw.githubusercontent.com/Memba/www.memba.com/master/fr/posts/2014/mean.png)

Grace à [nodeJS](https://nodejs.org/) et [expressJS](http://expressjs.com/), les [blocs MEAN](https://en.wikipedia.org/wiki/MEAN_(software_bundle)) offrent finalement un langage unique,
[JavaScript](https://en.wikipedia.org/wiki/JavaScript), pour écrire du code pour les navigateurs et les serveurs. La combinaison de nodeJS et expressJS constitue un environnement serveur simple mais puissant.

Pour être exact, nous n’utilisons pas le A - AngularJS – dans les blocs MEAN, mais ceci changera peut-être quand [AngularJS](https://angularjs.org/) sera plus mature.
À la place, [jQuery](http://jquery.com/) et le [framework Kendo UI](http://www.telerik.com/kendo-ui), notamment pour MVVM et les composants d’interface utilisateur, sont les fondations de notre code client.

Malgré l’absence de transaction et de jointure, nous avons trouvé [mongoDB](http://www.mongodb.org) extrêmement intuitif, robuste et performant. Nous apprécions la recherche plein texte intégrée dans le moteur de base de données.

### Phonegap

Les blocs MEAN et [Phonegap](http://phonegap.com/) fonctionnent en harmonie quand il s’agit de partager une API JSON RESTful entre une application mobile et l’interface utilisateur d’un site web.

### Docker sur AWS

Notre environnement technique serait incomplet sans un environnement de production qui est fourni par la combinaison de [Amazon Web Services](https://aws.amazon.com/) et [Docker](https://www.docker.com/).
Docker nous d’assembler des blocs de code dans des conteneurs qui sont ensuite facilement déployés sur AWS.