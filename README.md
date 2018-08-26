# Matterhorn scripts

This is a collection of scripts written for Matterhorn.

The scripts must be put in `~/.config/matterhorn/scripts/`, and all scripts must have execute permission for user (`chmod u+x <script>`). Execute the scripts inside the Matterhorn message window with this command: `/sh <script>`.

## Announce

Requirements: Python 3

### Usage

#### Single line:
```
> /sh announce Hello
```

Result:
```
#############
#           #
#   HELLO   #
#           #
#############
```


#### Multiline:
```
/sh announce Hi
Today is a new day

─[2/2]────────In multi-line mode. Press M-e to finish.────────
```

Result:
```
##########################
#                        #
#           HI           #
#   TODAY IS A NEW DAY   #
#                        #
##########################

```

#### Custom border:
```
/sh announce $
cash is the king

─[2/2]────────In multi-line mode. Press M-e to finish.────────
```

Result:
```
$$$$$$$$$$$$$$$$$$$$$$$$
$                      $
$   CASH IS THE KING   $
$                      $
$$$$$$$$$$$$$$$$$$$$$$$$
```
