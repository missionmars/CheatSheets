# Git Cheat Sheet

### Start new repo
```bash
git init .
```

### View all remote streams
```bash
git remote -v
```
### Push your local repository to remote
```bash
git remote add origin https:// ...
git push -u origin master
```

### Clear Port & Run Django Server
```bash
sudo fuser -k 8001/tcp; python manage.py runserver 192.168.0.2:8081 
```
