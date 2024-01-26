# tmux
## installation
``` sh
sudo apt install tmux
```
- create a session
``` sh
tmux
```
- create more windows
  1. vertically --> crtl + b + %
  2. horizontally --> crtl + b + "
- move from one to another --> crtl + b +  arrow key
- delete a window --> crtl + b + x + y
- exit a session --> crtl + b + d
- resume session `tmux a` (most recent)
- name a session
``` sh
tmux new -s <name>
```
- see all sessions `tmux ls`
- resume old session
``` sh
tmux a -t <name or index of session(tmux ls)>
```
- delete a session
``` sh
tmux kill-session -t <name or index of session(tmux ls)>
```
- 
