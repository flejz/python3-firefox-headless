### Python 3 container for Selenium + Firefox automation processes. ###

Contains:
* python 3.6.1
* pip 9.0.1
* firefox
* xvfb
* xauth
* geckodriver

**Dockerfile sample**
```sh
FROM jaimelopesflores/python3-firefox-headless
COPY . /app
WORKDIR /app
RUN pip install -r requirements.txt
CMD [ "python", "./your-script.py" ]
```
