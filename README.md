# **copysite command-line program for UNIX **

COPYSITE is a command-line program to create a local website copy from any online website.

You can to access the local site copy using http://localhost:1024/www.yoursitecopy.com in your web browser.



**It requires the Python interpreter, version 2.6, 2.7, or 3.2+ and wget installed.**


# **copysite URL** #

### Dependencies ###

* Python 
* Wget

# Install #

To install it right away for all UNIX users (Linux, OS X, etc.), copy and paste on terminal:


```
#!shell

sudo wget https://bitbucket.org/bneves/copysite/raw/d870e47461329ced096666253683a1e552146902/copysite -O /usr/local/bin/copysite
sudo chmod a+rx /usr/local/bin/copysite
```

or 


```
#!shell

sudo curl -L https://bitbucket.org/bneves/copysite/raw/d870e47461329ced096666253683a1e552146902/copysite -o /usr/local/bin/copysite
sudo chmod a+rx /usr/local/bin/copysite
```
