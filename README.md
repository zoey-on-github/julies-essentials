# julies-essentials
what i consider to be the "essential  mods" i "need" to play mc


# How do I actually install this pack?

## With packwiz and prismlauncher/multimc
clone this 
cd to dir where this is cloned at
run `packwiz serve`
download packwiz-installer-bootstrap from https://github.com/packwiz/packwiz-installer-bootstrap/releases and place it in the instance Minecraft folder \
(this part may confuse you if youre using prism launcher like i am because you tried to place the jar in your %appdata%/.minecraft folder but prism keeps a per-instance .minecraft folder, you can see where this is by [checking the log for that instance](https://files.catbox.moe/rymwss.png) )  
go to edit instance, instance comamnds, and paste this into prelaunch commands: `"$INST_JAVA" -jar packwiz-installer-bootstrap.jar  http://localhost:8080/pack.toml`  
that's it, you can launch now.  

## Without packwiz

download the latest .zip file from the releases  
you can add this as a new instance to prism launcher and whatnot  

### without packwiz, and with the offical launcher  
download the .zip file from the [releases](https://github.com/zoey-on-github/julies-essentials/releases/)  
unzip it, and go into the .minecraft folder, copy the mods and config folders into your %appdata%/.minecraft  
