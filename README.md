# Jime
###Options
* Round To options
  * minutes
  * minutes list
* Loop Seconds, 0 for no loop
* Round Up options
  * minutes
  * percentage of minutes in current interval

###Configuration
The Round To, Loop Seconds, and Round Up options are implemented in `jime.cfg`.

You may use only one Round To option (`round_to_min` or `round_to_min_list`).

You may use only one Round Up option (`round_up_min` or `round_up_per`).



####Examples:
```
# Default configuration
round_to_min=5
loop_sec=30
round_up_min=2
```
```
# This round to minutes list combines 10 and 15 minute intervals
round_to_min_list=[0,10,15,20,30,40,45,50]
loop_sec=10
round_up_per=40
```