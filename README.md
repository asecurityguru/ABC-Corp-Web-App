
ABC Corp Web Application 
=========
Quick start
----

Run the following command:
```
$ python3 dsvw.py 
Damn Small Vulnerable Web (DSVW) < 100 LoC (Lines of Code) #v0.2a

[i] running HTTP server at 'http://127.0.0.1:65412'...
```

and navigate your browser to http://127.0.0.1:65412/:


Requirements
----

Python (**3.x**) is required for running this program. Items *XML External Entity (local)*, *XML External Entity (remote)* and *Blind XPath Injection (boolean)* require installation of `python-lxml` (e.g. `apt-get install python-lxml`). Otherwise, those will be disabled.

To install lxml via pip, run the following command:

```
pip install -r requirements.txt
```
