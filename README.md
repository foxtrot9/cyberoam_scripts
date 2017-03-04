Cyberoam Client in Bash

=======================

A simple collection of bash scripts to handle cyberoam login and logout. Uses curl and cron.

Instructions
------------

* Make CyberroamConfig file in folder in which scipt resides.
* Put in you username and password.
```#!/bin/bash
                                                                                       
USER="201401448"
PASSWORD="xxxxxxxxxxxx"                                                               
URL="https://10.100.56.55:8090"```
 
* Edit Cyboroam URL.
* To login: `./login.sh`
* To logout: `./logout.sh`

