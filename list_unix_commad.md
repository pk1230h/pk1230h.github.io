# List of commands
## brew
```
brew install --cask [CASK] # install the cask(application) and manage by homebrew
ex: brew install --cask visual-studio-code

brew home [FORMULA] # open the home page of the formula

brew search [KEY_WORD_OF_FORMULA_OR_CASK] # search available formulae or casks

brew info [FORMULA_OR_CASK] # basic information of formula or cask
```

## tree
```
tree -L [1...n] [PATH] # show tree structure on given path or current folder
```

## z
```
z # show the frequency of using the directory
z [KEYWORD_OF_FOLDER] # move to matching directory
```

## history
```
history #show the terminal history of all typing
```
## psgrep
```
psgrep -a | grep [KEYWORDS] #find all process related to keywoard
```
## du
```
du -sh # total size in the current directory in human-readable format
du -h # show all files size under the current directory in human-readable format
du -h -d [NUMBER] # show all files/directories in level (0 is current) in human-readable format
```

## other commands
```
touch ~/.hushlogin #hide terminal login time

netstat -an | grep LISTEN  # check all port is listening
```
