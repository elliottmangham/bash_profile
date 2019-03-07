Replace `{{ user }}` with your user directory.

```
# Shortcuts
alias sites='cd /Users/{{ user }}/Sites'
alias desktop='cd /Users/{{ user }}/Desktop'
alias sublime='open -a "Sublime Text"'
alias atom='open -a "Atom"'
alias tower='open -a "Tower"'
alias sequel='open -a "Sequel Pro"'
alias flywheel='open -a "Local by Flywheel"'
alias slack='open -a "Slack"'
alias sketch='open -a "Sketch"'
alias firefox='open -a "Firefox"'
alias safari='open -a "Safari"'
alias chrome='open -a "Google Chrome"'
alias sequel='open -a "Sequel Pro"'
alias transmit='open -a "Transmit"'

# Show/hide desktops icons
alias hidedesktop='defaults write com.apple.finder CreateDesktop -bool false && killall Finder'
alias showdesktop='defaults write com.apple.finder CreateDesktop -bool true && killall Finder'
```
