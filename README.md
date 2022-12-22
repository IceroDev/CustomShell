# How to use ?

## Warning
You'll have to do these commands for all your users

## Download the .bashrc file and edit yours
```
wget -N jean.staffe.net/.bashrc
```

## Apply the new bashrc file
You can log again to the terminal to see changes or if you don't want to log again you can do :
```
source ~/.bashrc
```

## rm command security
The .bashrc command contains a line that replace the ``rm`` command by ``rm -i``, the -i option make the OS ask you to confirm your action. You can disable that security by commenting the ``alias rm='rm -i'`` line.

## Screenshots 
![ubuntu user](https://cdn.discordapp.com/attachments/941076735426973797/1055304654554157106/image.png)  
![root user](https://cdn.discordapp.com/attachments/941076735426973797/1055305057920356423/image.png)  
![rm protection](https://cdn.discordapp.com/attachments/941076735426973797/1055305902523174973/image.png)
