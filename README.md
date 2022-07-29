# Automated framework for secure software development using ethical hacking
Automated pentesting using docker and python.

### Main elements of our project:

    1. Containerization
    2. Pen testing
    3. Automation
    

### Containerization

* Docker based.
* Deployment image using docker file.
* Leave no trace – destroy the container.


### Pen testing

 Integrated three attacks.<br>
 
    * Cross site scripting [XSS].
    * SQL injection.
    * Password cracking.
    
    
### Automation

* Python based.
* Automated container lifecycle and pen testing attacks.
* Automated result generation and email notification.


## Test fuzzer locally on your host:

* #### Clone the repository

```sh
git clone https://github.com/chan2may/Automated-framework-for-secure-software-development-using-ethical-hacking.git
```

* #### Install Python3

```sh
sudo apt-get update && sudo apt-get install -y python3
```

* #### Install Docker

```sh
sudo apt-get update && sudo apt-get install -y docker.io
```

* #### Pull Python image

```sh
docker pull python
```

* #### Install and Run DVWA
```sh
docker pull vulnerables/web-dvwa
```
```sh
docker run -d -p 8000:80 vulnerables/web-dvwa
```

* #### Run python file

```sh
python3 main.py
```

## Resources
> [Pen testing attacks](https://github.com/saghal/webApplicationFuzzer)<br>
> [Docker](https://docs.docker.com/)<br>
> [Owasp zap](https://www.zaproxy.org/docs/docker/about/)<br>
> [E-mail automation](https://realpython.com/python-send-email/)<br>
> [How to Extract All Website Links in Python](https://www.thepythoncode.com/article/extract-all-website-links-python)<br>
> [xss payload list](https://github.com/payloadbox/xss-payload-list)<br>
> [Web Application Fuzzer](https://github.com/saghal/webApplicationFuzzer.git)

