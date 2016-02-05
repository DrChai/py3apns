# py3apns
A python3 version of [pyapns](https://github.com/samuraisam/pyapns)

### Intro
[pyapns](https://github.com/samuraisam/pyapns), a popular, fast, Python/Twisted based asynchronous push notification server for Apple Push Notification Services. This repo is used for Python3 environment. 

### Usage & Configuration
Same as original [pyapns](https://github.com/samuraisam/pyapns).
#### Notes
* Due to [Twisted](http://pypi.python.org/pypi/Twisted) currently doesnt full support python3(its Feb 2016). You have to run twistd using python2, for example:


      $ python2 /usr/bin/twistd web --class=pyapns.server.APNSServer --port=7077

* When performing batched notifications, the token and notification arrays must be exactly the same length.
