# Automated-pentesting
Automated pentesting using docker and python



## Test fuzzer locally on your host:
* #### install Docker

```sh
sudo apt-get update && sudo apt-get install -y docker.io
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
> [How to Extract All Website Links in Python](https://www.thepythoncode.com/article/extract-all-website-links-python)
> [xss payload list](https://github.com/payloadbox/xss-payload-list)
> [thepythoncode](https://www.thepythoncode.com)
