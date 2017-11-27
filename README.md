# CPE-Web
 
[![Join the chat at https://gitter.im/Computer-Engineering-UP/CPE-Website](https://badges.gitter.im/ThaiProgrammer/code-mania-110.svg)](https://gitter.im/Computer-Engineering-UP/CPE-Website)

Open Source Education Website
__Let’s start contributing to open source!__

- [Community Chat on Gitter.im](https://gitter.im/Computer-Engineering-UP/CPE-Website)
## Development environments 
1. Laravel PHP framework v5.5
2. Mysql
3. Docker (Nginx,PHP-FPM,Phpmyadmin)
# Contribution Cheatsheet

## Step 1 Fork

fork this GitHub (top-right button)

## Step 2 Clone

clone forked GitHub repo

```
$git clone https://github.com/CPEDevUp/cpe-web.git
```

where ```your-name``` is your GitHub ID

## Step 3 Setup
1. Install docker
- For window https://docs.docker.com/docker-for-windows/install/
- For Mac    https://docs.docker.com/docker-for-mac/install/
- For Ubuntu https://docs.docker.com/engine/installation/linux/docker-ce/ubuntu/

2. run docker
```
docker-compose up -d
```

3.Migrate database 
```
cd www/
composer migrate
```

## Step 4 Develop

- create a branch

```
$git checkout -b <branch-name>
```

- add untracked files

```
$git add .
```

- commit changes

```
$git commit -a -m "your short description"
```

- push changes

```
$git push origin <branch-name>
```


- switch branch to master

```
$git checkout master
```

- merge to master

```
$git merge <branch-name>
```

## Step 5 Pull Request

click send Pull Request button on your GitHub
