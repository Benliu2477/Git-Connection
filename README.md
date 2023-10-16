# Git-Connection-
This is a tutorial about how to connect with git in different IDE

在命令提示符中先输入：ssh-keygen -t ed25519
不要在后面加备注 \n
选择默认保存位置 \n
会产生两个文件，一个是public key : id_ed25519.pub, 另一个是private key : id_ed25519
复制public key里面的内容到git上面，然后创建SSH key
然后检测连接：在命令提示符里面输入ssh -T git@gitlab.example.com （将gitlab.example.com替换成你正在使用的git网站URL）

这样就连接成功了
