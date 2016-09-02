# baby-steps
TDD baby-step training tool as a bash script


**Help**

```
baby-steps [-h|?] [-v] [-m maximum] [-a action] [-i condition] [-t threshold] [-e <exclude>] path [path2] [... pathn] -- Run baby steps on paths

where:
    -h/?          show this help text
    -v            show decision tree on each file change event
    -e  exclude   file patterns to ignore
    -f  frequency change check frequency
    -m  maximum   maximum time with relevant changes trigger
    -a  action    command to call when max time trigger is reached
    -i  condition command to test, that when successful resets the timer
    -t  threshold progress to maximum threhold to start showing warnings
    path       	  root directory of files to watch
```
