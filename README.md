Cyberoam Client in Bash
=======================

A simple collection of bash scripts to handle cyberoam login and logout. Uses curl and cron.

Instructions
------------

* Make CyberoamConfig file in folder in which scipt resides.
* Put below contents in that file. Don't forget to edit `USER, PASSWORD and URL`.
```
#!/bin/bash
                                                                                       
USER="201401448"
PASSWORD="xxxxxxxxxxxx"                                                               
URL="https://10.100.56.55:8090"
```
* Make it readonly for better protection by using below command.
```
chmod +400 CyberoamConfig
```

* To login: `./login.sh`
* To logout: `./logout.sh`

