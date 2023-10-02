# 0x04. AirBnB clone - Web framework

## Resources

Read or watch:

- [What is a Web Framework?](https://intranet.alxswe.com/rltoken/64SQpOGx46Ljp0zFJchESg)
- [A Minimal Application](https://intranet.alxswe.com/rltoken/NopQlHIr9J_9OPX9XRgfvw)
- [Routing (except “HTTP Methods”)](https://intranet.alxswe.com/rltoken/cQiIhbSdIcg1Ao1MICseBg)
- [Rendering Templates](https://intranet.alxswe.com/rltoken/DBM65T59nySd0ZRlZZ0CXw)
- [Synopsis](https://intranet.alxswe.com/rltoken/5Y_A7XB9Qo1JeZgiSUq0yQ)
- [Variables](https://intranet.alxswe.com/rltoken/ITzobwYP1Lc4KqEUUcYCGw)
- [Comments](https://intranet.alxswe.com/rltoken/ykUFuQSE9KD1M7WGY-4v4w)
- [Whitespace Control](https://intranet.alxswe.com/rltoken/NMLZom50ZVOxQlgYW3rnuQ)
- [List of Control Structures (read up to “Call”)](https://intranet.alxswe.com/rltoken/5AGhzIt0zSpPJh9SFysdMQ)
- [Flask](https://intranet.alxswe.com/rltoken/VJs151_hsE9g7Cw-Pz5bVg)
- [Jinja](https://intranet.alxswe.com/rltoken/2y_hunzGCCvSot06EW67UQ)

### Install Flask

``` $ pip3 install Flask
```

## Tasks

### 0. Hello Flask!

Write a script that starts a Flask web application:

- Your web application must be listening on 0.0.0.0, port 5000
- Routes:
    - /: display “Hello HBNB!”
- You must use the option strict_slashes=False in your route definition

```
guillaume@ubuntu:~/AirBnB_v2$ python3 -m web_flask.0-hello_route
* Running on http://0.0.0.0:5000/ (Press CTRL+C to quit)
....
```

In another tab:

```
guillaume@ubuntu:~$ curl 0.0.0.0:5000 ; echo "" | cat -e
Hello HBNB!$
guillaume@ubuntu:~$
```

**Repo:**

- GitHub repository: `AirBnB_clone_v2`
- Directory: `web_flask`
- File: `0-hello_route.py, __init__.py`

### 1. HBNB

- Write a script that starts a Flask web application:

- Your web application must be listening on 0.0.0.0, port 5000
- Routes:
    - /: display “Hello HBNB!”
    - /hbnb: display “HBNB”
- You must use the option strict_slashes=False in your route definition

```
guillaume@ubuntu:~/AirBnB_v2$ python3 -m web_flask.1-hbnb_route
* Running on http://0.0.0.0:5000/ (Press CTRL+C to quit)
....
```

In another tab:

```
guillaume@ubuntu:~$ curl 0.0.0.0:5000/hbnb ; echo "" | cat -e
HBNB$
guillaume@ubuntu:~$
```

**Repo:**

- GitHub repository: `AirBnB_clone_v2`
- Directory: `web_flask`
- File: `1-hbnb_route.py`

