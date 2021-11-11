# My Message in a Bottle
Homework 2 – Advanced Software Service Engineering (2021/22)
The App is a time capsule where each user can send messages and decide the time and date when the recipient will be able to open them.



## Setup
To run this project:
* install the requirements

```$ python3.9 -m pip install -r requirements.txt```
* install redis server

```$ sudo apt install redis```
* run redis

```$ redis-server```
* run celery

```$ celery -A monolith.background worker -B```
* run the startup script

```$ bash run.sh```
