# tmux-script

tmux-script is a quick and dirty but powerful scripting solution for tmux. I developed it for a very simple purpose but later realized it's usefulness and decided to share it with the community.  It has essentially become a tool for managing and sending commands to tmux windows, and can be used in bash to issue a single command to all windows in a tmux session, or with a quick and simple script you write yourself. The syntax is very simple (have a look at the ```example_script```).

# Installation
- Download the tmux-script file, and copy it to ```/usr/local/bin/```
- Make sure you have tmux installed
- Make sure ```/usr/local/bin/``` is in your path
- Run ```mkdir ~/.tmux-script/``` from your terminal

# Usage

After you've written a script file and saved it in ```~/.tmux-script/```, you can run it with the command:
```tmux-script <name_of_your_script>```

You can also use it without a script, to run a single command on all open windows of a tmux session, like this:
```tmux-script all <name_of_tmux_session> '<command  to execute>'```
