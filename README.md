# Pylib Atlas

## Welcome to my Python toolbox!

This repository is dedicated to organizing and documenting useful Python programming tools and libraries across various categories, as well as other noteworthy resources. It is still a work in progress. 


Initially, this list started as a personal collection—a way for me to keep track of references and tools that I found invaluable in my coding journey. As the list grew and evolved, I decided to make it public with help from ChatGPT in hopes that it could serve as a resource for other developers. 

Whether you're a seasoned developer or just starting out, I hope you find this repository useful. 

As I continue to discover and learn about new tools and libraries, I plan to extend this list, making it an ever-growing resource for the programming community.


## Table of Contents

- [Web Frameworks](#-web-frameworks)
- [Machine Learning and AI](#-machine-learning-and-ai)
- [Data Science and analysis](#-data-science-and-analysis)
- [Image processing and computer vision](#-image-processing-and-computer-vision)
- [Networking and communication](#-networking-and-communication)
- [GUI Development](#-gui-development)
- [Database and ORM](#-database-and-orm)
- [Security and authentication](#-security-and-authentication)
- [Data Parsing and serialization](#-data-parsing-and-serialization)
- [Testing and QA](#-testing-and-qa)
- [Async and concurrency](#-async-and-concurrency)
- [Cryptography and hashing](#-cryptography-and-hashing)
- [CLI Utilities](#-cli-utilities)
- [Web scraping](#-web-scraping)
- [File and data manipulation](#-file-and-data-manipulation)
- [Framework extensions and plugins](#-framework-extensions-and-plugins)
- [Databases and time-series data](#-databases-and-time-series-data) 
- [Stream processing](#-stream-processing) 
- [DevOps and deployment](#-devops-and-deployment) 



---

## 🌐 Web Frameworks

| Library  | Description | Official Link |
| -------- | ----------- | ------------- |
| **Flask** | A lightweight WSGI web application framework in Python, designed for quick and easy web development. | [Flask](https://palletsprojects.com/p/flask/) |
| **Django** | A high-level Python web framework that encourages rapid development and clean, pragmatic design. | [Django](https://www.djangoproject.com/) |
| **Pyramid** | A lightweight Python web framework aimed at taking small web apps into big web apps. It is known for its flexibility and fine-grained control. | [Pyramid](https://trypyramid.com/) |
| **Tornado** | A Python web framework and asynchronous networking library, originally developed at FriendFeed. It is designed to handle asynchrony, enabling the development of real-time web applications. | [Tornado](https://www.tornadoweb.org/en/stable/) |
| **FastAPI** | A modern, fast (high-performance) web framework for building APIs with Python 3.7+ based on standard Python type hints, offering automatic Swagger UI documentation. | [FastAPI](https://fastapi.tiangolo.com/) |
| **Bottle** | A fast, simple, and lightweight WSGI micro web-framework for Python. It is distributed as a single file module and has no dependencies other than the Python Standard Library. | [Bottle](https://bottlepy.org/docs/dev/) |
| **CherryPy** | A minimalist Python web framework, making it easy to build web applications much like you would build any other object-oriented Python program. This results in smaller source code developed in less time. | [CherryPy](https://docs.cherrypy.dev/en/latest/) |


---

## 🤖 Machine Learning and AI

| Library | Description | Official Link |
| ------- | ----------- | ------------- |
| **TensorFlow** | An end-to-end open source platform for machine learning that enables researchers and developers to easily build and deploy ML powered applications. | [TensorFlow](https://www.tensorflow.org/) |
| **PyTorch** | An open source machine learning library based on the Torch library, used for applications such as computer vision and natural language processing. | [PyTorch](https://pytorch.org/) |
| **Scikit-learn** | A free software machine learning library for the Python programming language. It features various classification, regression, and clustering algorithms including support vector machines, random forests, gradient boosting, k-means and DBSCAN, and is designed to interoperate with the Python numerical and scientific libraries NumPy and SciPy. | [Scikit-learn](https://scikit-learn.org/stable/) |
| **Keras** | An open-source software library that provides a Python interface for artificial neural networks. Keras acts as an interface for the TensorFlow library. | [Keras](https://keras.io/) |
| **XGBoost** | A scalable, portable and distributed gradient boosting library, designed to efficiently perform the gradient boosting decision tree algorithm, popular for structured or tabular data. | [XGBoost](https://xgboost.ai/) |
| **LightGBM** | A gradient boosting framework that uses tree-based learning algorithms. It is designed for distributed and efficient training, particularly for high-dimensional data. | [LightGBM](https://lightgbm.readthedocs.io/en/latest/) |
| **CatBoost** | An open-source gradient boosting on decision trees library with categorical feature support out of the box, for machine learning. It yields state-of-the-art results without extensive data training typically required by other machine learning methods. | [CatBoost](https://catboost.ai/) |
| **spaCy** | An open-source library for advanced Natural Language Processing (NLP) in Python. It's designed specifically for production use and helps you build applications that process and "understand" large volumes of text. | [spaCy](https://spacy.io/) |
| **NLTK** | A leading platform for building Python programs to work with human language data. It provides easy-to-use interfaces to over 50 corpora and lexical resources such as WordNet, along with a suite of text processing libraries. | [NLTK](https://www.nltk.org/) |
| **Hugging Face Transformers** | A library for natural language processing (NLP) that provides thousands of pre-trained models to perform tasks on texts such as classification, information extraction, question answering, and more, implemented in TensorFlow and PyTorch. | [Hugging Face Transformers](https://huggingface.co/transformers/) |


---

## 📊 Data Science and analysis

| Library  | Description | Official Link |
| -------- | ----------- | ------------- |
| **Pandas** | An open source data analysis and manipulation tool, built on top of the Python programming language. | [Pandas](https://pandas.pydata.org/) |
| **NumPy** | A fundamental package for scientific computing with Python, providing support for large, multi-dimensional arrays and matrices. | [NumPy](https://numpy.org/) |
| **Matplotlib** | A plotting library for the Python programming language and its numerical mathematics extension NumPy. It provides an object-oriented API for embedding plots into applications. | [Matplotlib](https://matplotlib.org/) |
| **SciPy** | An open-source Python library used for scientific computing and technical computing. It builds on NumPy and provides a large number of higher-level functions that operate on numpy arrays and are useful for different types of scientific and engineering applications. | [SciPy](https://www.scipy.org/) |
| **Seaborn** | A Python data visualization library based on matplotlib. It provides a high-level interface for drawing attractive and informative statistical graphics. | [Seaborn](https://seaborn.pydata.org/) |
| **Plotly** | An open-source graphing library that makes interactive, publication-quality graphs online. Offers over 40 unique chart types covering a wide range of statistical, financial, geographic, scientific, and 3-dimensional use-cases. | [Plotly](https://plotly.com/python/) |
| **Bokeh** | A Python interactive visualization library that targets modern web browsers for presentation. Its goal is to provide elegant, concise construction of versatile graphics, and to extend this capability with high-performance interactivity over very large or streaming datasets. | [Bokeh](https://bokeh.org/) |
| **Dask** | An open-source library for parallel computing written in Python. Designed to scale from a single computer to a cluster, Dask provides advanced parallelism for analytics, enabling performance at scale for the tools you love. | [Dask](https://dask.org/) |

---

## 🖼️ Image processing and computer vision

| Tool | Description | Official Link |
| ---- | ----------- | ------------- |
| **OpenCV** | OpenCV (Open Source Computer Vision Library) is an open-source computer vision and machine learning software library. OpenCV was built to provide a common infrastructure for computer vision applications and to accelerate the use of machine perception. | [OpenCV](https://opencv.org/) |
| **scikit-image** | scikit-image is a collection of algorithms for image processing in Python. It is a free software project that is heavily used in academia, industry, and research. | [scikit-image](https://scikit-image.org/) |
| **SimpleCV** | SimpleCV is an open-source framework for building computer vision applications. It provides a consistent interface in Python for image acquisition, processing, and analysis. | [SimpleCV](http://simplecv.org/) |
| **Mahotas** | Mahotas is a computer vision and image processing library for Python. It includes a variety of algorithms for segmentation, feature extraction, and image manipulation. | [Mahotas](https://mahotas.readthedocs.io/en/latest/) |

---

## 🛜 Networking and communication

| Library | Description | Official Link |
| ------- | ----------- | ------------- |
| **Requests** | A simple, yet elegant HTTP library for Python, built for human beings. | [Requests](https://requests.readthedocs.io/en/master/) |
| **aiohttp** | An asynchronous HTTP client/server framework for asyncio and Python. | [aiohttp](https://aiohttp.readthedocs.io/en/stable/) |
| **HTTPx** | A fully featured HTTP client for Python 3, which provides synchronous and asynchronous APIs, and support for HTTP/2. | [HTTPx](https://www.python-httpx.org/) |
| **urllib3** | A powerful, user-friendly HTTP client for Python. Much of the Python ecosystem uses urllib3 and makes HTTP requests. It brings many critical features that are missing from the Python standard libraries. | [urllib3](https://urllib3.readthedocs.io/en/latest/) |
| **gRPC** | A high performance, open-source universal RPC framework that uses HTTP/2 as transport protocol, enabling client and server applications to communicate transparently and build connected systems. | [gRPC](https://grpc.io/) |
| **WebSocket-client** | A WebSocket client for Python with a focus on correctness and simplicity, providing easy access to WebSocket services. | [WebSocket-client](https://websocket-client.readthedocs.io/en/latest/) |
| **Paramiko** | A Python implementation of the SSHv2 protocol, providing both client and server functionality. It allows for easy SSH connections to remote servers. | [Paramiko](http://www.paramiko.org/) |
| **Netmiko** | A multi-vendor library to simplify Paramiko SSH connections to network devices. It's used extensively in network automation scripts. | [Netmiko](https://netmiko.readthedocs.io/en/latest/) |
| **Scapy** | A powerful Python program that enables the user to send, sniff, dissect and forge network packets. This capability allows for a wide range of networking tasks. | [Scapy](https://scapy.net/) |
| **Twisted** | An event-driven networking engine written in Python. Twisted runs on Python 2 and 3, and provides modules to deal with various protocols. | [Twisted](https://twistedmatrix.com/trac/) |


---

## 🖥️ GUI Development

| Library | Description | Official Link |
| ------- | ----------- | ------------- |
| **Tkinter** | The standard GUI toolkit for Python, providing a powerful object-oriented interface to the Tk GUI toolkit. | [Tkinter Documentation](https://docs.python.org/3/library/tkinter.html) |
| **PyQt** | A set of Python bindings for The Qt Company’s Qt application framework, used for developing GUI applications. | [PyQt](https://riverbankcomputing.com/software/pyqt/intro) |
| **Kivy** | An open-source Python library for developing multitouch application software with a natural user interface (NUI). | [Kivy](https://kivy.org/) |
| **wxPython** | A cross-platform GUI toolkit for the Python language, allowing Python programmers to create programs with a robust, highly functional graphical user interface, simply and easily. | [wxPython](https://www.wxpython.org/) |
| **PyGTK** | A set of Python wrappers for the GTK graphical user interface library, facilitating the creation of graphical interfaces in Python. | [PyGTK](https://pygtk.org/) |
| **PySide** | The official set of Python bindings for the Qt Company’s Qt application framework, similar to PyQt but under a more liberal license. | [PySide](https://www.qt.io/qt-for-python) |
| **Dear PyGui** | A simple to use (but powerful) Python GUI framework. DPG is a GPU Accelerated Python GUI framework for making quick, but advanced GUI applications. | [Dear PyGui](https://github.com/hoffstadt/DearPyGui) |
| **FLTK** | A cross-platform C++ GUI toolkit for UNIX®/Linux® (X11), Microsoft® Windows®, and MacOS® X. FLTK provides modern GUI functionality without the bloat and supports 3D graphics via OpenGL® and its built-in GLUT emulation. | [FLTK](https://www.fltk.org/) |

---

## 🗃️ Database and ORM

| Library | Description | Official Link |
| ------- | ----------- | ------------- |
| **SQLAlchemy** | A SQL toolkit and Object-Relational Mapping (ORM) library for Python that provides a full suite of well known enterprise-level persistence patterns. | [SQLAlchemy](https://www.sqlalchemy.org/) |
| **Django ORM** | Django's Object-Relational Mapper; a powerful tool for bridging the gap between the high-level Python code and the low-level database query. | [Django ORM](https://docs.djangoproject.com/en/3.0/topics/db/models/) |
| **Peewee** | A small, expressive ORM that provides a simple and intuitive way to interact with databases using Python. | [Peewee](http://docs.peewee-orm.com/en/latest/) |
| **SQLObject** | A popular ORM that provides an object-oriented interface to your database, with tables as classes, rows as instances, and columns as attributes. | [SQLObject](http://sqlobject.org/) |
| **Tortoise ORM** | An easy-to-use asyncio ORM (Object Relational Mapper) inspired by Django, designed for use with asyncio and Python. | [Tortoise ORM](https://tortoise.github.io) |
| **Pony ORM** | A Python ORM that provides a generator-based interface to write queries. It translates Python functions into SQL syntax and is designed for ease of use. | [Pony ORM](https://ponyorm.org/) |
| **MongoEngine** | A Document-Object Mapper for working with MongoDB from Python. It uses a simple declarative API, similar to the Django ORM. | [MongoEngine](http://mongoengine.org/) |
| **Django REST Framework** | A powerful and flexible toolkit for building Web APIs on top of Django, including ORM capabilities for working with databases through RESTful APIs. | [Django REST Framework](https://www.django-rest-framework.org/) |
| **Alembic** | A lightweight database migration tool for use with SQLAlchemy. It allows for version control for database schemas, enabling fine-grained and database-independent migration scripting. | [Alembic](https://alembic.sqlalchemy.org/en/latest/) |


---

## 🔒 Security and authentication

| Library | Description | Official Link |
| ------- | ----------- | ------------- |
| **OAuthLib** | A generic, spec-compliant, thorough implementation of the OAuth request-signing logic for Python. | [OAuthLib](https://oauthlib.readthedocs.io/en/latest/) |
| **PyJWT** | A Python library which allows you to encode and decode JSON Web Tokens (JWT). | [PyJWT](https://pyjwt.readthedocs.io/en/latest/) |
| **Authlib** | A comprehensive, ready-to-use library for OAuth 1, OAuth 2, OpenID clients, JWT, and other authentication protocols. | [Authlib](https://authlib.org/) |
| **python-social-auth** | A social authentication/registration mechanism with support for several frameworks and auth providers. | [python-social-auth](https://python-social-auth.readthedocs.io/en/latest/) |
| **Passlib** | A password hashing library for Python, providing over 30 schemes and a simple framework for managing existing password hashes. | [Passlib](https://passlib.readthedocs.io/en/stable/) |
| **Paramiko** | A module for Python 2.7/3.4+ that implements the SSHv2 protocol for secure (encrypted and authenticated) connections to remote machines. | [Paramiko](http://www.paramiko.org/) |


---


---

## 📜 Data parsing and serialization

| Library | Description | Official Link |
| ------- | ----------- | ------------- |
| **Beautiful Soup** | A library that makes it easy to scrape information from web pages, providing Pythonic idioms for iterating, searching, and modifying the parse tree. | [Beautiful Soup](https://www.crummy.com/software/BeautifulSoup/) |
| **lxml** | A powerful and Pythonic XML processing library combining libxml2/libxslt with the ElementTree API. | [lxml](https://lxml.de/) |
| **json** | The built-in JSON library in Python for encoding and decoding JSON data. | [json - Python Documentation](https://docs.python.org/3/library/json.html) |
| **Pandas** | While primarily a data analysis library, Pandas offers robust IO tools for reading and writing data in various formats, including CSV, Excel, JSON, HTML, and SQL databases. | [Pandas IO Tools](https://pandas.pydata.org/pandas-docs/stable/user_guide/io.html) |
| **PyYAML** | A YAML parser and emitter for Python, allowing for the serialization and deserialization of complex data structures to and from YAML, a human-friendly data serialization standard. | [PyYAML](https://pyyaml.org/) |
| **Marshmallow** | An ORM/ODM/framework-agnostic library for converting complex data types, such as objects, to and from native Python datatypes. | [Marshmallow](https://marshmallow.readthedocs.io/en/stable/) |
| **Protobuf** | Google's language-neutral, platform-neutral, extensible mechanism for serializing structured data, similar to XML but smaller, faster, and simpler. | [Protobuf](https://developers.google.com/protocol-buffers) |


---

## 🧪 Testing and QA

| Library | Description | Official Link |
| ------- | ----------- | ------------- |
| **pytest** | A framework that makes it easy to write small tests, yet scales to support complex functional testing for applications and libraries. | [pytest](https://pytest.org/) |
| **Selenium** | A portable framework for testing web applications, providing a playback tool for authoring functional tests. | [Selenium](https://www.selenium.dev/) |
| **unittest** | The built-in Python framework for writing and running tests, based on the xUnit pattern. | [unittest - Python Documentation](https://docs.python.org/3/library/unittest.html) |
| **nose2** | The successor to nose, extends unittest to make testing easier. It's less popular now due to pytest's rise, but it's still a powerful tool. | [nose2](https://docs.nose2.io/en/latest/) |
| **Robot Framework** | A generic open source automation framework for acceptance testing, acceptance test-driven development (ATDD), and robotic process automation (RPA). | [Robot Framework](https://robotframework.org/) |
| **Locust** | An easy-to-use, distributed user load testing tool. It's intended for load testing web sites (or other systems) and figuring out how many concurrent users a system can handle. | [Locust](https://locust.io/) |
| **Tox** | A generic virtualenv management and test command-line tool you can use for checking your package installs correctly with different Python versions and interpreters. | [Tox](https://tox.readthedocs.io/en/latest/) |
| **Hypothesis** | A powerful, flexible, and easy-to-use library for property-based testing. It lets you write tests that are parameterized by a source of examples. | [Hypothesis](https://hypothesis.works/) |
| **Behave** | For behavior-driven development (BDD), Behave uses tests written in a natural language style, backed up by Python code. | [Behave](https://behave.readthedocs.io/en/stable/) |

---

## ⚡ Async and concurrency

| Library | Description | Official Link |
| ------- | ----------- | ------------- |
| **asyncio** | The asyncio library is used to write concurrent code using the async/await syntax in Python. | [asyncio](https://docs.python.org/3/library/asyncio.html) |
| **gevent** | A coroutine-based Python networking library that uses greenlet to provide a high-level synchronous API on top of the libev or libuv event loop. | [gevent](http://www.gevent.org/) |
| **concurrent.futures** | A high-level interface for asynchronously executing callables. It provides a framework for asynchronously executing functions using threads or processes. | [concurrent.futures](https://docs.python.org/3/library/concurrent.futures.html) |
| **Twisted** | An event-driven networking engine written in Python, which can be used for asynchronous programming. | [Twisted](https://twistedmatrix.com/trac/) |
| **Tornado** | A Python web framework and asynchronous networking library that can handle thousands of connections at the same time. | [Tornado](https://www.tornadoweb.org/en/stable/) |
| **Celery** | An asynchronous task queue/job queue based on distributed message passing. It is focused on real-time operation, but supports scheduling as well. | [Celery](http://www.celeryproject.org/) |

---

## 🔐 Cryptography and hashing

| Library | Description | Official Link |
| ------- | ----------- | ------------- |
| **cryptography** | A package designed to expose cryptographic primitives and recipes to Python developers, offering both high-level recipes and low-level interfaces to common cryptographic algorithms. | [cryptography](https://cryptography.io/en/latest/) |
| **hashlib** | A module that implements a common interface to many secure hash and message digest algorithms, including SHA1, SHA224, SHA256, SHA384, SHA512, and MD5. | [hashlib](https://docs.python.org/3/library/hashlib.html) |
| **PyCryptodome** | A self-contained Python package of low-level cryptographic primitives. It is a fork of PyCrypto that has been enhanced and is actively maintained, designed to replace PyCrypto. | [PyCryptodome](https://www.pycryptodome.org/) |
| **Paramiko** | While known for its SSH2 protocol support, Paramiko also includes cryptographic functions and utilities as part of its core. | [Paramiko](http://www.paramiko.org/) |
| **NaCl (libsodium)** | A high-level cryptographic library that makes it easy to encrypt, decrypt, sign, and verify signatures without needing to manage nonces, keys, or other cryptographic details. | [NaCl (PyNaCl)](https://pynacl.readthedocs.io/en/latest/) |
| **OpenSSL** | A robust, full-featured toolkit for the Transport Layer Security (TLS) and Secure Sockets Layer (SSL) protocols. The `pyOpenSSL` library is a thin wrapper around (a subset of) the OpenSSL library. | [pyOpenSSL](https://www.pyopenssl.org/en/stable/) |


## ⌨️ CLI Utilities

| Library | Description | Official Link |
| ------- | ----------- | ------------- |
| **Click** | A Python package for creating beautiful command line interfaces in a composable way with as little code as necessary. | [Click](https://click.palletsprojects.com/) |
| **argparse** | The argparse module makes it easy to write user-friendly command-line interfaces. The program defines what arguments it requires, and argparse will figure out how to parse those out of sys.argv. | [argparse](https://docs.python.org/3/library/argparse.html) |
| **Typer** | A library for building CLI applications that users will love using and developers will love creating. Based on Python 3.6+ type hints. | [Typer](https://typer.tiangolo.com/) |
| **Docopt** | Helps you define your command-line interfaces by parsing the help message that your program prints to the user. | [Docopt](http://docopt.org/) |
| **Fire** | A library for automatically generating command line interfaces (CLIs) with a single line of code. It turns any Python module, class, or object into a CLI. | [Fire](https://github.com/google/python-fire) |
| **Plumbum** | Plumbum: Shell Combinators and More. It offers local and remote command execution, including command piping, file and path manipulation, and more, aiming for a more Pythonic interface. | [Plumbum](https://plumbum.readthedocs.io/en/latest/) |
| **Rich** | Although not exclusively a CLI library, Rich can be used to enhance the visual appeal of command line applications with rich text and beautiful formatting. | [Rich](https://rich.readthedocs.io/en/latest/) |

---

## 🕸️ Web Scraping

| Library | Description | Official Link |
| ------- | ----------- | ------------- |
| **Scrapy** | An open source and collaborative framework for extracting the data you need from websites in a fast, simple, yet extensible way. | [Scrapy](https://scrapy.org/) |
| **Beautiful Soup** | A library for pulling data out of HTML and XML files. It provides idiomatic ways of navigating, searching, and modifying the parse tree. | [Beautiful Soup](https://www.crummy.com/software/BeautifulSoup/) |
| **lxml** | While also a powerful XML and HTML processing library, lxml's speed and ease of use make it great for web scraping. | [lxml](https://lxml.de/) |
| **Requests-HTML** | An HTML parsing library designed to simplify the process of making requests and parsing HTML documents. It integrates functionality from requests and pyquery/pyppeteer for a comprehensive scraping solution. | [Requests-HTML](https://html.python-requests.org/) |
| **Selenium** | Although primarily a tool for testing web applications, Selenium can be used for scraping dynamic content that other tools can't handle as it allows for rendering JavaScript. | [Selenium](https://www.selenium.dev/) |
| **MechanicalSoup** | A Python library for automating interaction with websites. It combines the Requests library and BeautifulSoup to simulate a browser without a graphical interface. | [MechanicalSoup](https://mechanicalsoup.readthedocs.io/en/stable/) |
| **Puppeteer** (Pyppeteer) | A library for controlling headless Chrome or Chromium over the DevTools Protocol. Pyppeteer is the Python version, perfect for tasks requiring JavaScript rendering. | [Pyppeteer](https://github.com/pyppeteer/pyppeteer) |

---

## 📂 File and data manipulation

| Library | Description | Official Link |
| ------- | ----------- | ------------- |
| **Pillow** | The Python Imaging Library adds image processing capabilities to your Python interpreter. This library provides extensive file format support, an efficient internal representation, and fairly powerful image processing capabilities. | [Pillow](https://python-pillow.org/) |
| **CSV** | A module that implements classes to read and write tabular data in CSV format. It allows programmers to write and read data in a format preferred by Excel, without knowing the precise details of the CSV format. | [CSV Documentation](https://docs.python.org/3/library/csv.html) |
| **openpyxl** | A Python library to read/write Excel 2010 xlsx/xlsm/xltx/xltm files. | [openpyxl](https://openpyxl.readthedocs.io/en/stable/) |
| **Pandas** | Offers powerful data manipulation and analysis via its DataFrame object. It can read and write data in various formats, including CSV, Excel, JSON, HTML, and SQL databases. | [Pandas](https://pandas.pydata.org/) |
| **json** | The built-in JSON library for Python. It can parse JSON from strings or files and can convert dictionaries into JSON strings. | [json](https://docs.python.org/3/library/json.html) |
| **PyPDF2** | A library capable of splitting, merging together, cropping, and transforming the pages of PDF files. | [PyPDF2](https://pypdf2.readthedocs.io/en/latest/) |
| **xlrd/xlwt** | Libraries for reading data and formatting information from Excel files in the historic .xls format. | [xlrd](https://xlrd.readthedocs.io/en/latest/) / [xlwt](https://xlwt.readthedocs.io/en/latest/) |

---

## 🛠️ Framework extensions and plugins

| Library | Description | Official Link |
| ------- | ----------- | ------------- |
| **Flask-Login** | Provides user session management for Flask. It handles the common tasks of logging in, logging out, and remembering your users' sessions over extended periods of time. | [Flask-Login](https://flask-login.readthedocs.io/en/latest/) |
| **Django REST Framework** | A powerful and flexible toolkit for building Web APIs. It's a lightweight extension to Django that works well with existing apps and comes bundled with a set of serialization that can be customized and extended. | [Django REST Framework](https://www.django-rest-framework.org/) |
| **Flask-RESTful** | An extension for Flask that adds support for quickly building REST APIs. It is a lightweight abstraction that works with your existing ORM/libraries. | [Flask-RESTful](https://flask-restful.readthedocs.io/en/latest/) |
| **Flask-SQLAlchemy** | Adds SQLAlchemy support to Flask. It simplifies the use of SQLAlchemy with Flask by providing useful defaults and extra helpers that make it easier to accomplish common tasks. | [Flask-SQLAlchemy](https://flask-sqlalchemy.palletsprojects.com/en/2.x/) |
| **Django-Allauth** | Provides authentication, registration, account management as well as 3rd party (social) account authentication. | [Django-Allauth](https://django-allauth.readthedocs.io/en/latest/) |
| **React Router** | While not a Python library, React Router is a powerful routing library for React that allows the creation of single page applications with dynamic page changes without the need to reload. Useful for Django or Flask backends serving React frontends. | [React Router](https://reactrouter.com/) |
| **Vue Router** | Similar to React Router but for Vue.js. It enables the development of powerful single-page web applications. This can be useful in projects that use Python backends. | [Vue Router](https://router.vuejs.org/) |


---

## 🗄️ Databases and time-series data

| Tool           | Description | Official Link |
|----------------| ----------- | ------------- |
| **Prometheus** | An open-source system monitoring and alerting toolkit originally built at SoundCloud, now part of the Cloud Native Computing Foundation. It's focused on reliability and scalability, handling multi-dimensional data collected over time. | [Prometheus](https://prometheus.io/) |
| **InfluxDB**   | An open-source time series database designed to handle high write and query loads. It is a component of the TICK stack. | [InfluxDB](https://www.influxdata.com/) |
| **SQLite**     | A C-language library that implements a small, fast, self-contained, high-reliability, full-featured, SQL database engine. SQLite is the most used database engine in the world. | [SQLite](https://www.sqlite.org/index.html) |
| **PostgreSQL** | A powerful, open source object-relational database system with over 30 years of active development. | [PostgreSQL](https://www.postgresql.org/) |
| **MongoDB**    | A general purpose, document-based, distributed database built for modern application developers and for the cloud era. | [MongoDB](https://www.mongodb.com/) |
| **GraphQL**    | A query language for APIs and a runtime for executing those queries by using a type system you define for your data. It enables declarative data fetching, allowing clients to specify exactly what data they need.	| [GraphQL](https://graphql.org)|


---

## 🌊 Stream processing

| Tool | Description | Official Link |
| ---- | ----------- | ------------- |
| **Apache Kafka** | A distributed event streaming platform capable of handling trillions of events a day. Initially conceived as a messaging queue, Kafka is based on an abstraction of a distributed commit log. | [Apache Kafka](https://kafka.apache.org/) |
| **RabbitMQ** | An open-source message-broker software that originally implemented the Advanced Message Queuing Protocol (AMQP) and has since been extended with a plug-in architecture to support Streaming Text Oriented Messaging Protocol (STOMP), MQTT, and other protocols. | [RabbitMQ](https://www.rabbitmq.com/) |
| **Apache Pulsar** | A cloud-native, distributed messaging and streaming platform originally created at Yahoo! It's designed to provide a highly scalable, durable, and secure event streaming platform. | [Apache Pulsar](https://pulsar.apache.org/) |
| **Redis Streams** | A new data type introduced in Redis 5.0, which provides a series of features that make it possible to handle streams of data directly within Redis. | [Redis Streams](https://redis.io/topics/streams-intro) |


---

## 🚀 DevOps and deployment

| Library | Description | Official Link |
| ------- | ----------- | ------------- |
| **Docker** | An open platform for developing, shipping, and running applications, Docker enables you to separate your applications from your infrastructure so you can deliver software quickly. | [Docker](https://www.docker.com/) |
| **Kubernetes** | An open-source system for automating deployment, scaling, and management of containerized applications. | [Kubernetes](https://kubernetes.io/) |
| **Ansible** | An open-source automation tool, or platform, used for IT tasks such as configuration management, application deployment, intra-service orchestration, and provisioning. | [Ansible](https://www.ansible.com/) |
| **Fabric** | A high-level Python library designed to execute shell commands remotely over SSH, facilitating application deployment and system administration tasks. | [Fabric](https://www.fabfile.org/) |
| **Terraform** | An open-source infrastructure as code software tool that provides a consistent CLI workflow to manage hundreds of cloud services. Terraform codifies cloud APIs into declarative configuration files. | [Terraform](https://www.terraform.io/) |
| **GitLab CI/CD** | A tool built into GitLab for software development through the continuous methodologies: Continuous Integration (CI), Continuous Delivery (CD), and Continuous Deployment (CD). | [GitLab CI/CD](https://docs.gitlab.com/ee/ci/) |
| **Jenkins** | An open-source automation server that enables developers around the world to reliably build, test, and deploy their software. | [Jenkins](https://www.jenkins.io/) |
| **Python Jenkins** | A Python wrapper for the Jenkins REST API which allows you to access Jenkins servers. This can be used to automate Jenkins server management, job configuration, and job execution. | [Python Jenkins](https://python-jenkins.readthedocs.io/en/latest/) |
| **Minikube** | Minikube is a tool that makes it easy to run Kubernetes locally. Minikube runs a single-node Kubernetes cluster inside a VM on your laptop for users looking to try out Kubernetes or develop with it day-to-day. | [Minikube](https://minikube.sigs.k8s.io/docs/) |
| **Helm** | The package manager for Kubernetes. Helm helps you manage Kubernetes applications — Helm Charts help you define, install, and upgrade even the most complex Kubernetes application. | [Helm](https://helm.sh/) |

