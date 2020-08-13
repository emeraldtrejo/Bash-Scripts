# Bash-Scripts
Add Script to cron file by following commands:

crontab -e

add following code to ping every 15 seconds
* * * * * sleep 00; timeout 15s <path of script file>.sh
* * * * * sleep 15; timeout 15s <path of script file>.sh
* * * * * sleep 30; timeout 15s <path of script file>.sh
* * * * * sleep 45; timeout 15s <path of script file>

check cron jobs
crontab -l
