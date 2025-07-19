# Change-Default-Home-Directory-In-Termux-Permanently

## First
```
pwd
```

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
