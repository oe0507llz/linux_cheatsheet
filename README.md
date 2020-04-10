# linux_cheatsheet

#### Find Linux Files by Name or Extension
https://www.linode.com/docs/tools-reference/tools/find-files-in-linux-using-the-command-line/
```
find /home/username/ -name "*.err"
```

#### Working with JSON in bash using jq
https://cameronnokes.com/blog/working-with-json-in-bash-using-jq/

### Search for a word from all the files in the current directory
```
grep -rnw ./ -e 'Web Services Key'
```

#### 5 Ways to Check Available Memory in Ubuntu
https://vitux.com/5-ways-to-check-available-memory-in-ubuntu/
```
free -m
```

### Task Scheduling with Crontab on Mac
Have to use `sudo`, otherwise it won't work:
```
sudo crontab -e
sudo crontab -l
```

#### Crontab run every 15 minutes except at 3AM?
https://stackoverflow.com/questions/8764150/crontab-run-every-15-minutes-except-at-3am
```
*/15 0-2,4-23 * * * thejob
```
#### What should I do to run a script on specific time without cron?
https://unix.stackexchange.com/questions/511807/what-should-i-do-to-run-a-script-on-specific-time-without-cron
