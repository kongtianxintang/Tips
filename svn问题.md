####  此文记录svn所遇到的问题
-  Directory 'xx' is out of date
-  在工程当前目录下
```
svn update
```
- a peg revision is not allowed here
```
在图片路径后面加@即可
svn add "xxx@2x.png@"
```
- 用命令行添加所有未控制文件
```
svn st | awk '{if ( $1 == "?") { print $2}}' | xargs svn add
```
