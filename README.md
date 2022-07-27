# Automated framework for secure software development using ethical hacking
Automated pentesting using docker and python.

### Main elements of our project:

    1. Containerization
    2. Pen testing
    3. Automation
    

## Containerization

* We have used docker for building containers.
* We are Building our own image using a docker file.
* Containers are destroyed at the end.

## Pen testing



## Test fuzzer locally on your host:
* #### install Docker

```sh
sudo apt-get update && sudo apt-get install -y docker.io
```

* #### Pull Python image

```sh
docker pull python
```

* #### install and run DVWA
```sh
docker pull vulnerables/web-dvwa
```
```sh
docker run -d -p 8000:80 vulnerables/web-dvwa
```
## demo
![](demo.gif)
## Resources
> [How to Extract All Website Links in Python](https://www.thepythoncode.com/article/extract-all-website-links-python)<br>
> [xss payload list](https://github.com/payloadbox/xss-payload-list)

