# dev-setup

# Terminal:

## Preference:
![alt text](dev-setup/preference_command.jpg "Terminal command preference")
![alt tag](dev-setup/preference_color.jpg "Terminal preference - color")

## Include current path in the title for terminal
Edit - vim ~/.bashrc
Add - PROMPT_COMMAND='echo -ne "\033]0;${USER}@${HOSTNAME}: ${PWD}\007"'
