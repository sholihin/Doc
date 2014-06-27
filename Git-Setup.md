#### Konfigurasi GIT ####

##### Git global setup: #####

```
git config --global user.name "Mohamad Sholihin"
git config --global user.email "mohamad.sholihin.it@gmail.com"
```

##### Create Repository: #####

```
mkdir belajar-springboot
cd belajar-springboot
git init
touch README
git add README
git commit -m 'first commit'
git remote add origin git@git.ngoprek.org:sholihin/belajar-springboot.git
git push -u origin master
```

##### Existing Git Repo: #####

```
cd existing_git_repo
git remote add origin git@git.ngoprek.org:sholihin/belajar-springboot.git
git push -u origin master
```
