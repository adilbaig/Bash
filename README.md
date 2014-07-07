Bash
====

Bash Tips, shortcuts

See the age of a process
----
Get the PID of the process, then run this.

````
date -d @$(stat -t /proc/<PID> | awk '{print $14}')
````
