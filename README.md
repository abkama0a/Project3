# Linux Server Configuration
Third project of Udacity Fullstack Nano Degree program
A project about configuring a linux server and hosting the Catalog web app in a real server

## Table of Contents

- [Table of Contents](#table-of-contents)
- [IP Address](#ip-address)
- [Complete URL](#complete-url)
- [Software Summary](#software-summary)
- [Configuration Summary](#configuration-summary)

## IP Address
IP Address: [18.185.184.41.xip.io](http://18.185.184.41.xip.io)

SSH port 2200

## Complete URL

## Software Installed
1. finger
2. apache web server
3. postgresql
4. sqlite3
5. pip
6. git

## Configuration Summary
1. Add user: grader with disabled password
2. Disable password login and only allow ssh key-based login
3. Turn on UFW and only allow SSH over 2200, HTTP over 80, and NTP over 123
4. Setup virtual enviroment to run my catalog app on apache
6. Add virtual enviroment configuration to apache default.conf file
5. Add `export LC_ALL=C` to fix locale issues with some pip commands
6. Install all the modules necessary to run the catalog web app using pip & a requirements.txt file
7. In catalog web app python script, change all relative paths to absolute ones

[(Back to TOC)](#table-of-contents)