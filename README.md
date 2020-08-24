# Important Linux/Ubuntu commands for regular usage


### Check disk space

To check the total used space and available / free space use 
```
df -h
```
### Find the directory size
List the directories with their size

```
sudo du -hc --max-depth=1 /home/pragnakalp
```
```
sudo du -sh /home/pragnakalp
```

### Check the Memory/RAM usage

```
free -m
```

### View any file in terminal

```
cat filename.txt
```

### Check history of all commands
```
history
```

### Untar the files

```
tar -xvf  'test.tar.gz' -C '/destination/folder'
```

### Search for folder/directory in the whole system

```
find / -xdev 2>/dev/null -name "dirname"
```
or with * wild card
```
sudo find / -name dirnam* -type d
```

### Search/find the file in 
```
locate filename | grep filename
```
