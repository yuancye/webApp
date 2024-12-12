1. create a project folder named 'webApp'
# frontend
2. download node.js
3. ```npx create-react-app frontend```
4. cd frontend
5. ```rm -rf .git``
6. add the git config
   ```
   git init
   git config user.name "yuancye"
   git config user.email "yuanchaoye1986@gmail.com"
   ```
7. create an empty git repository without readme.md
```
git remote add origin https://github.com/yuancye/webApp.git
git add . 
git commit -m "create the frontend using react"
git branch -M main
git push origin main
```
# postgreSQL
1. download postgreSQL: https://www.postgresql.org/download
2. brew install postgresql@15 -> working on it
3. 
# backend
1. install python3 if not
2. create a fodler named 'backend' and cd backend
3. create django project
```
python3 -m venv django
rm -rf .git
source django/bin/activate
pip install django
pip install psycopg2
```


note: 
git errors
1. your local branch is behind the remote branch
```
git pull --rebase origin main
```