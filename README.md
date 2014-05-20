app
===

another simple python app for GAE

The simplest app will have only 2 files: 
app.yaml and some python code for a request handler (main.py in this example)

Python request handler scripts use the CGI protocol for communicating with App Engine.
CGI protocol can be implemented directly, but in real applications web frameworks like
Django, web2py and Pylons are used

App engine includes simplest framework "webapp" 
Memcache service can be used as secondary storage for user preferences data. 
The memcache stores key-value pairs, with an op- tional namespace for the key.
To make the caching behavior more visible, add logging statements 
