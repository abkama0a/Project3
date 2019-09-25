# Linux Server Configuration
```
Third project of Udacity Fullstack Nano Degree program
A project about configuring a linux server and hosting the Catalog web app in a real server
```
## Table of Contents

- [Table of Contents](#table-of-contents)
- [IP Address](#ip-address)
- [Complete URL](#complete-url)
- [Software Summary](#software-summary)
- [Configuration Summary](#configuration-summary)
- [Third Party Resources](#third-party-resources)

## IP Address
* IP Address: [18.185.184.41.xip.io](http://18.185.184.41.xip.io)
* SSH port **2200**
* Account **grader**:
```
 Use this account to access the server with SSH using the provided key during the project submition.

 This account has no password and the provided key has no passphrase
```

## Complete URL

## Software Installed
1. finger
2. apache web server
3. postgresql
4. sqlite3
5. pip
6. git
7. virtualenv
8. unattended-upgrade

## Configuration Summary
1. Add user: grader with disabled password
2. Disable password login and only allow ssh key-based login
3. Turn on UFW and only allow SSH over 2200, HTTP over 80, and NTP over 123
4. Setup virtual enviroment to run my catalog app on apache
6. Add virtual enviroment configuration to Project2.conf file and activate it as a website
5. Add `export LC_ALL=C` to fix locale issues with some pip commands
6. Install all the modules necessary to run the catalog web app using pip & a requirements.txt file
7. In catalog web app python script, change all relative paths to absolute ones

## Third Party Resources
##### 1. Udacity Fulllstack Nano Degree program source materials & community - [Udacity](https://www.udacity.com)
##### 2. Amazon Web Serivces Documentation - [Managing users](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/managing-users.html)
##### 2. Upgrading kept-back packages - [askubuntu](https://askubuntu.com/questions/601/the-following-packages-have-been-kept-back-why-and-how-do-i-solve-it)
##### 3. xip.io wildcard DNS provider - [xip.io](http://xip.io)
##### 4. Deploy Flask app on Apache Server - [Digital Ocean](https://www.digitalocean.com/community/tutorials/how-to-deploy-a-flask-application-on-an-ubuntu-vps) - [mod_wsgi Docs](https://modwsgi.readthedocs.io/en/develop/user-guides/virtual-environments.html#virtual-environment-and-python-version) - [Medium](###https://medium.com/@esteininger/###python-3-5-flask-apache2-mod-wsgi3-on-ubuntu-16-04-67894abf9f70)
##### 5. Setting up enviromental variables for Apache - [GitHub](https://gist.github.com/GrahamDumpleton/b380652b768e81a7f60c)
##### 6. Stackoverflow for general issues faced -[StackOverflow](https://stackoverflow.com)

   Some particular problems I faced and got solutions for:
   * [relative path problem in flask app running on Apache](https://stackoverflow.com/questions/37901716/flask-uploads-ioerror-errno-2-no-such-file-or-directory)
   * [database read-write problem on Apache](https://stackoverflow.com/questions/40703228/python-sqlite3-operationalerror-attempt-to-write-a-readonly-database)


[(Back to TOC)](#table-of-contents)