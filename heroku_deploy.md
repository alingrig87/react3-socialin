### Deploying app to heroku

1. Download and install heroku cli or install via npm

```bash
   npm install -g heroku
```

2. Clone the app from github

```bash
   git clone <app_repo_url.git>
   cd <new_cloned_app_name>
```

3. Login to heroku from git bash command line

```bash
   heroku login
```

4. Link git repository to heroku app

```bash
   heroku git:remote -a <app_name_from_heroku>
```

5. Deploy last changes to heroku (master on main branch)

```bash
   git push heroku master
   or
   git push heroku main
```
