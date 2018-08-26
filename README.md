## Announce

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
