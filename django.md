#### Django Cheat Sheet

## Run server script - Shortcut

cd /usr/bin

sudo nano djrun

#!/bin/bash
sudo fuser -k [PORT]/tcp; python manage.py runserver [IP]:[PORT]
