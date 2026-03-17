# tofi-emoji
tofi-emoji is a fork of [wofi-emoji](https://github.com/Zeioth/wofi-emoji) and is an emoji selector which uses tofi, as opposed to wofi-emoji, which allows users to select emoji using wofi, not tofi: like tofi-emoji.  
[original author](https://github.com/dln)  
[wofi-emoji maintainer](https://github.com/Zeioth)

# dependencies
 - tofi
 - wtype
 - bash...

# usage
tofi-emoji uses the configfile _~/.config/tofi/config-emoji_. just symlink your main config if you'd like to reuse it.  
`ln ~/.config/tofi/config ~/.config/tofi/config-emoji`  

to use, bind a key in your compositor config to execute `tofi-emoji`.  
the executable or a symlink to it needs to be in a PATH directory (or provide a direct path in the keybinding)
