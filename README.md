Welcome to PIMF Blog bundle
===========================
This Blog is a run ready bundle, which uses PIMF framework including a blog application based on SQLite database.
Here you can learn how to work with Pimf_EntityManager, Pimf_Util_Validator and Pimf_View.

System Requirements
-------------------
This bundle has system requirements to PHP's extensions: "PDO" and "pdo_sqlite". The extentions
have to be compiled within your PHP. Please check by executing **php -m** on you command interface - and
take a look for them. If they are there than everything will be fine - otherwise please navigate
to http://www.php.net/manual/pdo.setup.php and find out how to recompile them to your PHP version.

Installation & Configuration
----------------------------

1. git clone --recursive https://github.com/gjerokrsteski/pimf-blog.git

2. cd pimf-blog/

3. git submodule foreach git pull origin master

4. php pimf core:init

Navigate to your application in a web browser. If all is well, you should see a pretty PIMF splash page. Get ready - there is lot more to learn!

Learning PIMF
-------------
One of the best ways to learn PIMF is to read through the entirety of its documentation. This guide details all aspects of the framework and how to apply them to your application. https://github.com/gjerokrsteski/pimf/wiki

Read the PIMF book almost anywhere. Available as a PDF, EPUB and MOBI. You can now read it on all devices, as well as offline: https://leanpub.com/pimf-starter/
