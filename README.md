# Aliases4terminal

## I. General
### 1. Git
```
alias glog="git log --graph --format=format:'%C(bold blue)%h%C(reset) - %C(bold green)(%ar)%C(reset) %C(white)%an%C(reset)%C(bold yellow)%d%C(reset) %C(dim white)- %s%C(reset)' --all"
```

## II. macOs
### 1. Spotlight
```
alias mds_off='sudo launchctl unload -w /System/Library/LaunchDaemons/com.apple.metadata.mds.plist'
alias mds_on='sudo launchctl load -w /System/Library/LaunchDaemons/com.apple.metadata.mds.plist'
```

### 2. Raw to jpeg
```
alias raw2jpg='for i in *.NEF; do sips -s format jpeg $i --out "${i%.*}.jpg"; done'
```




