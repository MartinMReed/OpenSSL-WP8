OpenSSL 1.0.1c with updates to compile for Windows Phone 8. The Visual Studio projects can be found under [`openssl-1.0.1c/vsbuild`](openssl-1.0.1c/vsbuild).

A Windows Phone Runtime Component class can be found under [`openssl-1.0.1c/vsbuild/OpenSSLWP8`](openssl-1.0.1c/vsbuild/OpenSSLWP8). It includes both a client a server example.  

This was based on a [StackOverflow answer](http://stackoverflow.com/a/17314901/2616171) from [Oliver Ciappara](http://stackoverflow.com/users/1105735/oliver-ciappara).

# WARNING
Parts of the OpenSSL source has been modified to compile against Windows Phone 8. Review the commits before using this code in production! This project was just a proof of concept to show that OpenSSL could be used.
