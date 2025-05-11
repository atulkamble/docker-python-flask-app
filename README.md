# docker-python-flask-app
Docker python Flask App
```
git clone https://github.com/atulkamble/docker-python-flask-app.git
cd docker-python-flask-app/
python app.py

sudo yum install pip
sudo pip install flask
python app.py
```

```
pip3 install flask
pip freeze > requirements.txt
docker build -t flask-app .
docker run -p 5000:5000 flask-app
sudo docker images
http://localhost:5000/
curl -sSfL https://raw.githubusercontent.com/docker/scout-cli/main/install.sh | sh
brew upgrade docker-scout
docker scout quickview flask-app
docker scout cves flask-app
docker scout recommendations flask-app
```
