# Check processes currently running

The following command will check if a process is currently running.

Running ps -ax | grep 'process' will run a few commands together - 
* ps will list processes
* ax will make check for processes all users are running and additionally those not running in the terminal
* pipe will combine commands before and after the pipe symbol
* grep will check pattern matches with the process name listed.

**example -** 

```
ps -ax | grep process-here
```