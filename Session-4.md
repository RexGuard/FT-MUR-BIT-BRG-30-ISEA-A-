## Session 4a
Rsync Lab

|Commands||
|:---|----|
|`rsync`|Copy and syncronize file between locations|

Syning VPS files to Local Folder
Vps Folder

![alt text](images/image-29.png)

run Rsync command from Local Computer

![alt text](images/image-30.png)

Rsync Copies file to local folder

![alt text](images/image-31.png)

- Difference between scp / cp
If rsync found a similar duplicate file, it will compare between them and only transfer the data byte/block that changed.