# tmux [cheatsheet](https://tmuxcheatsheet.com/)
## installation
``` sh
sudo apt install tmux
```
- create a session
``` sh
tmux
```
- create more panel
  1. vertically --> ctrl + b + %
  2. horizontally --> ctrl + b + "
- move from one to another --> ctrl + b +  q + panel number (displayed when you press first 3 keys)
  - or ctrl + b + arrowkey
- resize a panel --> ctrl + b + ctrl + arrowkey
  - preset layout --> ctrl + b + alt + {1-5}any
- delete a panel --> ctrl + b + x + y
- create multiple windows in one session --> ctrl + b + c
- shift between windows in a session -->  ctrl + b + n
- move anywhere -> ctrl + b + w
- exit a session --> ctrl + b + d
- resume session `tmux a` (most recent)
- Once you have selected the text, press “ctrl + w” to copy it to the Tmux clipboard. Next, press “ctrl + b” followed by “=.”
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
- delete all sessions
``` sh
tmux kill-server
```
- 
