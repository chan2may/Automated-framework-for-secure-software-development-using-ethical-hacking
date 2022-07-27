# Automated framework for secure software development using ethical hacking
Automated pentesting using docker and python.

### Main elements of our project:

    1. Containerization
    2. Pen testing
    3. Automation
    

### Containerization

* We have used docker for building containers.
* We are Building our own image using a docker file.
* Containers are destroyed at the end.

### Pen testing

 We have integrated three attacks in our project.<br>
    * *Cross site scripting [XSS].*<br>
    * *SQL injection.*<br>
    * *Password cracking.*<br>
 Report is generated at the end.
    
### Automation

* We have automated docker containers and pen testing attacks using python.
* We will be automatically sending the report via email.

## Test fuzzer locally on your host:

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
> [How to Extract All Website Links in Python](https://www.thepythoncode.com/article/extract-all-website-links-python)<br>
> [xss payload list](https://github.com/payloadbox/xss-payload-list)

