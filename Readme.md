# How to use it

## Step 1: Create a database on host machine

```
mysql> create database wdcem default character set utf8mb4;  #replace "wdcem" with your db name
```

## Step 2: Create your own project

Don't have to clone this repo. Just do the following: 

```
#Github supports "svn export". 

svn export https://github.com/chenjianjx/wordpress-docker-compose-except-mysql/trunk my-wp-project
cd my-wp-project 
```


## Step 3: Set variables 
Update .env

## Step 4: Run it

```
docker-compose up
```

# Credits
Inspired by https://github.com/nezhar/wordpress-docker-compose
