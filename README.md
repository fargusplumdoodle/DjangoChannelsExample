# DJANGO CHANNELS TUTORIAL

This is just following the django channels tutorial. It is mainly for
reference.

For client side implementation checkout the JS in `templates/chat/room.html`

For actual usage run:
```
pip3 install -r requirements.txt
docker run -p 6379:6379 -d redis:2.8
python3 manage.py makemigrations
python3 manage.py migrate
python3 manage.py runserver
```
Then open 2 seperate browser windows to:
 http://localhost:8000/chat/
 

Install firefox-geckodriver for tests to work

[This is the tutorial this was made from](https://channels.readthedocs.io/en/latest/tutorial/index.html)
