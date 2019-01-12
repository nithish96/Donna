# Donna - Simple Version Control
This project implements simple features of git like init, stage, commit and displaying logs. 

### Current features supported:
* init (Serves the same functionality like 'Git init')
```
    Usage:python main.py init
```
* stage(Serves the same functionality like 'Git stage')
```
    Usage:python main.py stage (filenames with space between each filename)
```
* commit(Serves the same functionality like 'Git commit')
```
    Usage:python main.py commit (commit message in double quotes)
```
* display(Displays the commit log and verison log on terminal)<
```
    Usage:python main.py display
```

### For more fun execution:

**Type the following in the terminal:**
```
alias donna = "python main.py"
```

Now, to execute the above features, replace "python main.py" with "donna". For example to run init ... type following on the terminal

```
    donna init
```
### Note
* This fun execution is valid for one terminal session and will disapear after closing the terminal(due to the limitations of "alias" command). So, for every new terminal session, please repeat the same instructions again for fun execution.
* If you need to make it permanent across multiple sessions add it to the .bashrc file and then source it.
* Add your access key in online function  in main.py to push code to your dropbox account.
~                                     
