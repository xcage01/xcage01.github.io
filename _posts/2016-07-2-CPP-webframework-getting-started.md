---
published: true
title: Cpp Webframework Getting Started
layout: post
---
Yesterday i started working on [Dragon](https://github.com/xcage01/octo-dragon)
which is my latest work-in-progress.Basically what i am trying to build is a 
sleek C++ framework that is end user friendly for creating web-applications.
The obvious motivation for the project was from 
[Django](https://www.djangoproject.com/) which is an awesome framework in python
and i have been using it extensively along with DRF for as long as i can 
remember. First i did a quick research and found a couple of frameworks that
were already providing functionality of a webframework in c++ but they seemed
too handson for me (which i don't mind anyways). But as it is said by django
team `django the web framework for perfectionists with deadlines` which is pretty
true from my experience.

Till now i have been able to expose a simple HTTP web server using [Libmicrohttpd](https://www.gnu.org/software/libmicrohttpd/) and a simple [Logger](https://github.com/easylogging/easyloggingpp). Now django uses modules for diffrent apps. The same was a little
tough in c++ so the best alternative that i could come up with was to define
namespace for all of them and to have an `init` function that registers the app.

Now what comes next is probably a lot of pain in my butt that includes but not
limited to ORM , form data handeling etc. Will try to finish the server today.
Luckily i found a guy on reddit who had written a similar ORM in c++. I am hoping
that some good pointers are coming from his side.

Finally i would very much appreciate if you can head over to repository and
look over the codes and pass on your suggestions. Because the package is in
eary stages of development all the suggestions and critique are appreciated and
welcome.

happy hacking !!