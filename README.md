# os

## linux

### vi-manual

Beginning
```bash
$ vi filename
```

after the start: **command mode**
commands are described by **1** letter  

#### insertion mode
| commands | corresponds |  
|:---|:---|
| i | insert at actual cursor position |   
| a | insert after actual cursor postion |  
| o | insert in a newl line after the actuel cursor postion |  

#### replacement mode

| command | corresponds |
|:---|:---|
| r | one character will be overwrite **and** subsequently automatic in command mode |
| R | At cursor postionen many characters can be overwritten |

#### command mode

| command | corresponds |
|:---|:---|
| x | delete actual character |
| dd | delete actual line (1 action in the buffer. Prefix a number sia a multiplicater, e.g. 3x, 4dd |
| u | undo last command |
| Y | (Yank) copies current line to buffer |
| p | insert buffer content after cursor postion **or** after actual line( if Buffer content is a hole line) |
| P | like p, just insert before |
| I | searching: subsequently enter the search term in the last line |
| n | Repetition of the last searching |
| d **and** p **or** P | move|

#### cursor positioning

| command | corresponds |
|:--- | :--- |
| h | right |
| k | up |
| I/j | left |
| j | down |

---
