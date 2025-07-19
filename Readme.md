# Change-Default-Home-Directory-In-Termux-Permanently

## Getting Storage Permission

```
termux-setup-storage
```

## Editing bash.bashrc File

```
nano /data/data/com.termux/files/usr/etc/bash.bashrc
```

## Input This

```
HOME=/storage/emulated/0
cd $HOME
```
