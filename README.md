# hello-world

> This is the tutorial repository.

-----

# The largest heading
## The second largest heading
### The 3rd largest heading
#### The 4th largest heading
###### The smallest heading

### git command
Some basic Git commands are:
```Shell
git status
git add
git commit
```

```
git status      # List all new or modified files
git diff        # Show file differences that haven't been staged
```

### table
| Command | Description |
| --- | --- |
| `git status` | List all *new or modified* files |
| `git diff` | Show file differences that **haven't been** staged |

### list
- list1
- list2

### comment out
```
<!-- this is hidden comment -->
```
<!-- this is hidden comment -->

### sample settings
```
sudo apt update
sudo apt install pigpio python3-pigpio
sudo systemctl enable pigpiod.service
sudo systemctl start pigpiod
echo 'm 17 w  w 17 0  m 18 r  pud 18 u' > /dev/pigpio

curl http://abyz.me.uk/rpi/pigpio/code/irrp_py.zip | zcat irrp.py
python3 irrp.py -r -g18 -f codes light:on --no-confirm --post 130
python3 irrp.py -p -g17 -f codes light:on
```

