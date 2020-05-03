#### Crtl + b = Standard Prefix Key 

The standard Prefix key is changed due to the custom configuration. So now the Prefix Key is Ctrl + a

#### Ctrl + a = Prefix Key 

To use this custom configuration please edit/create the .tmux.conf file, which can be found in your home directory.
```
vi ~/.tmux.conf
```
Use the config file attacked to this repo as a reference.

### general commands
```
tmux new -s HTB

Prefix + c = create new session

Prefix + 0, 1, 2, 3 = switch between sessions

Prefix + , = rename current session

Prefix + [ = enter edit mode vi

Prefix + Alt + Shift + P = saves the session to a log file
```
### splits
```
Prefix + % = vertical split

Prefix + " = horizontal split

Prefix + <arrow keys> = move arround

Prefix + { or } = move widows arround

Prefix + ? = tmux manual
```
