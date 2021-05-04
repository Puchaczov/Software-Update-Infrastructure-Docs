# What is this service all about

Soupinf.net is a service that provide supporting infrastructure for OTA (over the air) updates for applications that require such a feature. Everyone that had to code it yourself know how tedious tend to be to build up all surrounding infrastructure. You have to think of ...

1. how (and where!) to store updates
2. how to generate patches
3. how to update client application
4. where to store modules? should those be versioned to?

Generally speaking there is a lot of decisions to make, but after all your users will have aut-updates!

# Where should I use that?

Well, there might be potentatially many places but the most promising are IOT and desktop applications. You might think of applications like `Chrome` or `Steam` or just games, they are using OTA updates! It would be ridicolous to force their users to update applications manually with so fast publishing cycle. Especially when we would like our users to use the most recent version of our software, without bugs and with new features.

# What this service is promising to help with?

We can take care for the most of those boring tasks so

1. We provide a place your users can download your full version of software. Then:
2. We provide infrastructure to store your logically versioned patches. Ordered, ready for your users to download and apply regardless of version they have. Moreover
3. We can generate those patches for you with just a single line of code. It is so easy!
4. We provide statistics about users downloading your software
5. Many more like integrations with twitter, ability to create modules for your applications and others...

Of course we don't have to provide you all of these feature as in the end you are the person that understand what OTA update means in your specific use case and what features will be usable.

# API & Languages

There is separate section of what our API is capable of. The service itself is technology agnostic means that you can connect using any programming language (aka library) able to make a HTTPS request.
