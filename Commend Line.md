## 文件和目录操作
### pwd  
当前工作目录
### ls  
当前工作目录内容
### cd  
改变当前工作目录
### cp 
拷贝文件/目录
* `cp <file1> <file2>`  
拷贝文件
* `cp -r <dir1> <dir2>`  
拷贝目录
### mv
移动文件/目录
* `mv <file> <dir>`  
移动文件
* `mv <dir1> <dir2>`  
移动目录
### rm
删除文件/目录
* `rm <file>`  
删除文件
* `rm -r <dir>`  
删除目录
### touch
创建文件
* `touch <file>`
* `>file.txt`
### mkdir
创建目录
* `mkdir <dir>`
### cat
查看文件
* `cat <file>`
### file
查看文件类型
* `file <file>`
### echo
打印
* `echo *.txt`  
打印出符合条件的文件
### .zip
* `unzip <file.zip>`  
解压缩
* `zip -r <file.zip> <dir>`  
将dir中内容打包生成file.zip
### .tar.gz
* `tar zxvf <file.tar.gz>`  
解压缩
* `tar zcvf <file.tar.gz> <dir>`  
将dir中内容打包生成file.tar.gz
### .tar.bz2
* `tar jxvf <file.tar.bz2>`  
解压缩
* `tar jcvf <file.tar.bz2> <dir>`  
将dir中内容打包生成file.tar.bz2  

## 权限
### chmod
更改文件/目录权限
* `chmod a+x <file/dir>`&`chmod +x <file/dir>`  
all添加执行权限
* `chmod u+w <file/dir>`  
user添加写权限
* `chmod g+rwx <file/dir>`  
group添加所有权限
* `chmod o-rw <file/dir>`  
others删除读写权限
