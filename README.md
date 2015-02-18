# mod_incapsula



  Apache module for [Incapsula.com](http://incapsula.com) backends


    git clone https://github.com/usefulz/mod_incapsula
    cd mod_incapsula/
    apxs -c -i -a mod_incapsula.c

* Add the following to httpd.conf


        LoadModule incapsula_module modules/mod_incapsula.so


* Restart Apache
