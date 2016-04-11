---
category: Divers
description: Memba a choisi nodeJS, expressJS, mongoDB et phonegap pour construire ses solutions logicielles.
icon: leaf
keywords: Memba, Kidoju, Microsoft, Visual, Basic, C++, J++, C#, Studio, Silverlight, Java, MTS, SQL, MySQL, Oracle, logiciel libre, informatique dématérialisée, Amazon, AWS, Apple, iOS, Android, JavaScript, nodeJS, MEAN
language: fr
title: Phonegap et l'architecture MEAN
uuid: 3fb02190-a955-11e5-9b32-4dc425266d67
author: jlchereau
author_url: https://github.com/jlchereau
avatar_url: https://avatars.githubusercontent.com/u/2556751?v=3
creation_date: 2014-12-23T09:11:34Z
edit_url: https://github.com/Memba/www.memba.com/blob/master/fr/posts/2014/mean.md
site_url: http://www.memba.com/fr/posts/2014/12/mean
---
### Not so long ago

Memba has long been a Microsoft shop and we used to be a Microsoft ISV and Microsoft partner. 
Our development team has had experience with Visual Basic, Visual C++, Visual J++ and Visual Studio .NET including C#.

Like most object oriented gurus, we have never been big fans of HTML. We also had this strong feeling that the mix of languages and technical architecture of web applications could be streamlined.
 
### The MEAN stack

![MEAN stack](https://raw.githubusercontent.com/Memba/www.memba.com/master/en/posts/2014/mean.png)

Thanks to [nodeJS](https://nodejs.org/) and [expressJS](http://expressjs.com/), the [MEAN stack](https://en.wikipedia.org/wiki/MEAN_(software_bundle)) finally offers one single language,
[JavaScript](https://en.wikipedia.org/wiki/JavaScript), to build code for browsers and servers. The combination of nodeJS and expressJS is a very simple yet powerful server environment.

To be fair, we do not use the A - AngularJS - in the MEAN stack, but this may change once [AngularJS](https://angularjs.org/) gets more mature.
Instead, [jQuery](http://jquery.com/) and the [Kendo UI framework](http://www.telerik.com/kendo-ui), especially for MVVM and UI widgets, are the foundations of our client code.

Despite the lack of atomic transactions and joins, we have found [mongoDB](http://www.mongodb.org) extremely intuitive, reliable and performing. We appreciate full-text search being built into the engine.

### Phonegap

The MEAN stack and [Phonegap](http://phonegap.com/) play well together especially when sharing a RESTful JSON API between a mobile application and a web UI.

### Docker on AWS

Our technical environment would not be complete without a production environment which is provided by the combination of [Amazon Web Services](https://aws.amazon.com/) and [Docker](https://www.docker.com/).
Docker allows us to componentize server code into containers which can easily be deployed on AWS.



Memba a longtemps été une boutique Microsoft et nous étions même Microsoft ISV et Microsoft Partner.
Notre équipe de développement a réalisé des projets en Visual Basic, Visual C++, Visual J++ et Visual Studio .NET, notamment C#.
C’est fini pour les raisons suivantes.

### Les errements de Microsoft

Nous avons réalisé une grand projet en Visual J++ avec Microsoft Transaction Server (MTS) et SQL Server and quand Microsoft a abandonné Visual J++,
nous avons perdu beaucoup d’argent à migrer vers Tomcat et Oracle.

En tant que gurus de l’orienté objet, nous n’étions pas des fans d’HTML dont nous trouvions l’architecture, en particulier la [séparation des préoccupations](https://en.wikipedia.org/wiki/Separation_of_concerns), maladroite.
Quand Microsoft a sorti Silverlight, nous avons vu de multiples bénéfices dans cette technologie, mais Microsoft a aussi abandonné Silverlight et nous nous sommes alors promis : PLUS JAMAIS!

### Logiciel libre

Entre temps, le logiciel libre a été une révolution chez les développeurs, menée par les communautés Java, MySQL et Linux.
La promesse de Java, "write once, run anywhere", n’a pas été totalement respectée, en particulier dans le navigateur, mais Linux a garanti
la possibilité d’exécuter du code Java sur toutes tailles de serveurs du PI zero](https://en.wikipedia.org/wiki/Raspberry_Pi) au [zSeries](https://en.wikipedia.org/wiki/IBM_System_z). 

### L’informatique dématérialisée 

Les développeurs doivent maintenant construire pour l’informatique dématérialisée, notamment Amazon AWS.
Le matériel informatique ne concerne plus les développeurs, ce qui a rendu [Wintel](https://en.wikipedia.org/wiki/Wintel) complètement obsolète à part pour exécuter Microsoft Office.
Amazon AWS est essentiellement un environnement d’exécution Linux et s'il peut ne pas être souhaitable de développer sous Linux,
par exemple dans le cas où Microsoft Office et Adobe Creative Suite seraient requis, [Apple OSX](http://www.apple.com/uk/osx/) est l’environnement le plus proche que l’on puisse trouver. 

### Les terminaux mobiles

Les terminaux mobiles tournent majoritairement sous iOS et Android et Microsoft a aussi perdu cette bataille.

### La pile MEAN

La [pile MEAN](https://en.wikipedia.org/wiki/MEAN_(software_bundle)) ne nous a pas seulement réconciliés avec HTML.
Nous avons enfin un seul langage, [JavaScript](https://en.wikipedia.org/wiki/JavaScript), pour construire du code pour les navigateurs et les serveurs.

![Logo MEAN](https://raw.githubusercontent.com/Memba/www.memba.com/master/fr/posts/2014/mean.png)