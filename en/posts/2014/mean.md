---
category: Miscellaneous
description: Memba is now commited to nodeJS, expressJS, mongoDB and phonegap.
icon: leaf
keywords: Memba, Kidoju, Microsoft, Visual, Basic, C++, J++, C#, Studio, Silverlight, Java, MTS, SQL, MySQL, Oracle, open source, cloud, Amazon, AWS, Apple, iOS, Android, JavaScript, nodeJS, MEAN
language: en
title: Phonegap and the MEAN stack
uuid: e1c0a470-a94e-11e5-9b32-4dc425266d67
author: jlchereau
author_url: https://github.com/jlchereau
avatar_url: https://avatars.githubusercontent.com/u/2556751?v=3
creation_date: 2014-12-23T08:26:02Z
edit_url: https://github.com/Memba/www.memba.com/blob/master/en/posts/2014/mean.md
site_url: https://www.memba.com/en/posts/2014/12/mean
---
### Not so long ago

Memba has long been a Microsoft shop and we used to be a Microsoft ISV and Microsoft partner. 
Our development team has had experience with Visual Basic, Visual C++, Visual J++ and Visual Studio .NET including C#.

Like most object oriented gurus, we have never been big fans of HTML. We also had this strong feeling that the mix of languages and technical architecture of web applications could be streamlined,
also considering the frustration of working with black boxes.

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