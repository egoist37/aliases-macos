# Aliases4terminal
+ macOs


###Spotlight
```
alias mds_off='sudo launchctl unload -w /System/Library/LaunchDaemons/com.apple.metadata.mds.plist'
alias mds_on='sudo launchctl load -w /System/Library/LaunchDaemons/com.apple.metadata.mds.plist'
```




###Raw to jpeg
```
alias raw2jpg='for i in *.NEF; do sips -s format jpeg $i --out "${i%.*}.jpg"; done'
```
