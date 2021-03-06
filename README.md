[![Black Hat Arsenal](https://raw.githubusercontent.com/toolswatch/badges/master/arsenal/usa/2018.svg?sanitize=true)](http://www.toolswatch.org/2018/05/black-hat-arsenal-usa-2018-the-w0w-lineup/)

# Resilient-ML-Research-Platform 

(This doc is under construction)

This is a web platform to demo Machine Learning as a Service (MLaaS) on security researches. 
It has a machine learning (ML) pipeline to analyze data and also is a portal for backend user to emulate uploaded binaries.
It demos adversarial ML and countermeasures.

## Getting Started
### Prerequisites
* Apache Hadoop & Spark
* MongoDB
* Scikit-Learn, Numpy, Keras and related Python packages
* Django & SQLite
* for Python 2.7 only

### Installing
* (TBD) One-click installation by Docker containers...
* Please follow the [Setup_Guide_CentOS7.pdf](Setup_Guide_CentOS7.pdf) for installation
* Modify web files app.config, myml/settings.py, atdml/settings.py for Hadoop/Spark/web/MongoDB hostnames

## Design Diagrams
### Architecture:
<img src="../master/atdml/static/atdml/img/mlaas_arch_gpu.png" height="320">

### Software Stack:
<img src="../master/atdml/static/atdml/img/sw_stack.png" height="200">

Note: backend robots and DNN worker are not included in this project.

## License
This project is licensed under the Apache 2.0 


