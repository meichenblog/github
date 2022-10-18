# GitHub 与 Git 的使用

[git](https://www.yiibai.com/git/git_config.html)

## 查看Git所有配置以及他们所在的文件：

```bash
git config --list --show-origin
```

![image-20211224175501423](C:\Users\MTL\AppData\Roaming\Typora\typora-user-images\image-20211224175501423.png)

```bash
git config --global user.name "John Doe"		# Git上配置GitHub用户名称
git config --global user.email "johndoe.example.com"   	# Git上配置GItHub注册邮箱
```



Git本地创建key钥

```bash
ssh-keygen -t ed25519 -N '' -f ~/.ssh/id_ed25519
```

把生成的id_rsa.pub的信息添加到Github的SSH and GPG Keys中

GitHub添加key

![image-20220110161324976](C:\Users\MTL\AppData\Roaming\Typora\typora-user-images\image-20220110161324976.png)



![image-20220110161340542](C:\Users\MTL\AppData\Roaming\Typora\typora-user-images\image-20220110161340542.png)

```bash
echo "# IpadPro11" >> README.md
git init														    # 会在本地项目中，生成一个.git的文件
git add README.md												# 添加文件到仓库
git commit -m "first commit"						# 提交的文件注释说明，最好说明一下，否则有时会出错
git branch -M mei												 
git remote add origin https://github.com/meichenblog/IpadPro11.git # 将本地仓库关联到github的仓库里去
git push -u origin mei                  # 将代码提交到Github上
```
# 配置Github访问加速

https://github.com/oldj/SwitchHosts

https://swh.app/

https://github.com/521xueweihan/GitHub520

https://github.com/gauseen/
