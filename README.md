# Image Classification API using Tensorflow



[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)]

Image Classification API using Inception V3 running on Docker.

  - User Token based to allow the usage of the API.
  - Shows the type of image being fed in with confidence number.
  - Refills by the admin.

### Tech


requests
Image Classification API uses on the following libraries:

* [tensorflow] - TensorFlow is a Python-friendly open source library for numerical computation that makes machine learning faster and easier..
* [flask_restful] - Flask-RESTful is an extension for Flask that adds support for quickly building REST APIs. 
* [pymongo] - MongoDB is a document database with the scalability and flexibility that works with the querying and indexing.
* [bcrypt] - The bcrypt hashing function allows us to build a password security platform that can scale with computation power. 
* [Flask] - Flask is a web framework. It provides tools, libraries and technologies that allow to build a web application.
* [Docker] -A Docker container image is a lightweight, standalone, executable package of software that includes everything needed to run an application.
* [Numpy] - NumPy is the fundamental package for scientific computing with Python. It contains among other things: a powerful N-dimensional array object.


### Installation

Image Classification requires Docker and Docker Compose to run.

Install the dependencies.
Docker and Docker Compose from [DOCKER](https://docs.docker.com/compose/install/)
For [MongoDB](https://docs.mongodb.com/)


### To run the API:

```sh
$ docker-compose build
$ docker-compose up
```



License
Freeware
----




