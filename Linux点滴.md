# Learn_Linux

雁过留痕。

## 目录

- cd /home 进入 '/ home' 目录' 
- cd .. 返回上一级目录 
- cd ../.. 返回上两级目录 
- cd 进入个人的主目录 
- cd ~user1 进入个人的主目录 
- cd - 返回上次所在的目录 
- pwd 显示工作路径 
- mkdir dir1 创建一个叫做 'dir1' 的目录' 
- rm -rf dir1 删除一个叫做 'dir1' 的目录并同时删除其内容 
- mv dir1 new_dir 重命名/移动 一个目录 
- ls /usr/local  遍历 /usr/local 目录下的文件

## 文件

- ls 查看目录中的文件 
- ls -F 查看目录中的文件 
- ls -l 显示文件和目录的详细资料 
- ls -a 显示隐藏文件 
- rm -f file1 删除一个叫做 'file1' 的文件' 
- rm filename 删除文件
- ls *.doc 显示所有以 .doc 结尾的文件
- vi filename  如果filename文本文件存在，则打开，不存在，则创建名为filename文本文件，并打开，按下 i 键即可进入编辑模式，完成编辑后，可以按 esc 键退出编辑模式
- cat filename 打开filename文件
- cat -b filename 打开filename文件，并显示行号
- cp filename copyfile 复制文件
- touch 两个功能：一是用于把已存在文件的时间标签更新为系统当前的时间（默认方式），它们的数据将原封不动地保留下来；二是用来创建新的空文件。

## 系统

- shutdown -h now 关闭系统
- shutdown -r now 重启
- reboot 重启
- addHack XX 把文件xx放进flash，断电也可加载

## su 和 sudo 区别

- [详情](https://www.cnblogs.com/slgkaifa/p/6852884.html)