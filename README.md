## find 
### 在当前目录以及子目录递归查找指定文件名
find / -name "file.txt"

## grep 
### 在当前目录以及子目录递归查找指定关键字的文件
grep -r "key-words" ./

### 统计当前目录下文件的个数（不包括目录）
$ ls -l | grep "^-" | wc -l
### 统计当前目录下文件的个数（包括子目录）
$ ls -lR| grep "^-" | wc -l
### 查看某目录下文件夹(目录)的个数（包括子目录）
$ ls -lR | grep "^d" | wc -l
