Replace `{{ user }}` with your user directory.

```
# Shortcuts
alias sites='cd /Users/{{ user }}/Sites'
alias desktop='cd /Users/{{ user }}/Desktop'
alias sublime='open -a "Sublime Text"'
alias tower='open -a "Tower"'
alias chrome='open -a "Google Chrome"'

# Show/hide desktops icons
alias hidedesktop='defaults write com.apple.finder CreateDesktop -bool false && killall Finder'
alias showdesktop='defaults write com.apple.finder CreateDesktop -bool true && killall Finder'
```
