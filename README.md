```
██╗    ██╗  ██████╗  ██████╗  ██████╗      █████╗  ██████╗  ████████╗ 
██║    ██║ ██╔═══██╗ ██╔══██╗ ██╔══██╗    ██╔══██╗ ██╔══██╗ ╚══██╔══╝ 
██║ █╗ ██║ ██║   ██║ ██████╔╝ ██║  ██║    ███████║ ██████╔╝    ██║    
██║███╗██║ ██║   ██║ ██╔══██╗ ██║  ██║    ██╔══██║ ██╔══██╗    ██║    
╚███╔███╔╝ ╚██████╔╝ ██║  ██║ ██████╔╝    ██║  ██║ ██║  ██║    ██║    
 ╚══╝╚══╝   ╚═════╝  ╚═╝  ╚═╝ ╚═════╝     ╚═╝  ╚═╝ ╚═╝  ╚═╝    ╚═╝   
```
 single website file used to generate word art comments for code. Only need the [WordArt.html](WordArt.html) file and it will generate everything itself.

# parameters

|parameter| desction|
|-|-|
| text | Text to be converted into a title |
| start of each line | for turning the art into a comment, eg '#' for python |
| Start of each block | some coding languages need 'brackets' around a comment, eg '*/ for sql |
| End of each block | closing 'bracket' for comment, eg '/* for sql | 

# Accepted Text

- All leters, which will be capitilzed
- All numbers
- A few special characters: 
  - _  underscore
  - \- hyphen 
  - , comma
  - . full stop
  - / fore slash
  - ' ' space

Any charecter not found will return 'err'

 # Sizes
 have several options for sizes, recomend 5-6 lines to grab attention (eg for class titles) and 2 lines for sub-attention (eg for method title)

```
#Number of lines: 2

#   █ █ █ █▀█ █▀█ █▀▄    ▄▀█ █▀█ ▀█▀ 
#   ▀▄▀▄▀ █▄█ █▀▄ █▄▀    █▀█ █▀▄  █  
#



#Number of lines: 3

#   █   █ ▄▀▀▄ █▀▀▄ █▀▀▄    ▄▀▀▄ █▀▀▄ ▀▀█▀▀ 
#   █ █ █ █  █ █▄▄▀ █  █    █▄▄█ █▄▄▀   █   
#    █ █  ▀▄▄▀ █ ▀█ █▄▄▀    █  █ █ ▀█   █   
#



#Number of lines: 4

#   █   █ ▄▀▀▀▄ █▀▀▄ █▀▀▄    ▄▀▀▄ █▀▀▄ ▀▀█▀▀ 
#   █ █ █ █   █ █▄▄▀ █  █    █▄▄█ █▄▄▀   █   
#    █ █  █   █ █ ▀█ █  █    █  █ █ ▀█   █   
#    █ █  ▀▄▄▄▀ █  █ █▄▄▀    █  █ █  █   █   
#



#Number of lines: 5

#   ██     ██  ██████  ██████  ██████      █████  ██████  ████████ 
#   ██     ██ ██    ██ ██   ██ ██   ██    ██   ██ ██   ██    ██    
#   ██  █  ██ ██    ██ ██████  ██   ██    ███████ ██████     ██    
#   ██ ███ ██ ██    ██ ██   ██ ██   ██    ██   ██ ██   ██    ██    
#    ███ ███   ██████  ██   ██ ██████     ██   ██ ██   ██    ██    
#



#Number of lines: 6

#   ██╗    ██╗  ██████╗  ██████╗  ██████╗      █████╗  ██████╗  ████████╗ 
#   ██║    ██║ ██╔═══██╗ ██╔══██╗ ██╔══██╗    ██╔══██╗ ██╔══██╗ ╚══██╔══╝ 
#   ██║ █╗ ██║ ██║   ██║ ██████╔╝ ██║  ██║    ███████║ ██████╔╝    ██║    
#   ██║███╗██║ ██║   ██║ ██╔══██╗ ██║  ██║    ██╔══██║ ██╔══██╗    ██║    
#   ╚███╔███╔╝ ╚██████╔╝ ██║  ██║ ██████╔╝    ██║  ██║ ██║  ██║    ██║    
#    ╚══╝╚══╝   ╚═════╝  ╚═╝  ╚═╝ ╚═════╝     ╚═╝  ╚═╝ ╚═╝  ╚═╝    ╚═╝    
#
```