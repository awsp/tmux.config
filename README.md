TMUX Commands 
---
Basic commands based on the tmux.config


#### Windows Command
Alt + A then ...
```
c       New Window 
,       Name Window 
w       List Windows
f       Find Window
&       Kill Window
1..9    Navigate to Window with ID
.       Move Window 
```

#### Pane Command
Alt + A then ...
```
-       Horizontal Split
_       Vertical Split
x       Close Pane
hjkl    Navigate to Pane (Up, Down, Left, Right)
HJKL    Resize Pane (Up, Down, Left, Right)
q       Show Pane number
```

#### General Command
```
d       Detach session
```

### Tmux Basic Command
```
tmux		Start new session
tmux ls		List all sessions 
tmux attach-session -t [n] Re-attach session n
```


