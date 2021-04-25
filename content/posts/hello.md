+++
title = "Hello"
date = "2021-04-23T02:07:09+08:00"
author = ""
authorTwitter = "" #do not include @
cover = ""
tags = ["cfw", ""]
keywords = ["", ""]
description = ""
showFullContent = false
+++

## 1. Sign up for an MaxMind account  

- Visit MaxMind to regsiter
## 2. Download GeoLite2 Country database from MaxMind

- Go to your account -> Download files -> Download Binary(.mmdb) format of GeoLite2-Country edition
![maxmind](maxmind.png)

## 3. Update GeoIP database

- Open this path "%HOMEPATH%\.config\clash" if you are on windows  
- Rename Country.mmdb to Country.mmdb.old  
- Extract the database from the archive to the folder and rename it to   Country.mmdb 