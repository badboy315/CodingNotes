## oh-my-zsh 无法升级处理

### 问题

近日， 碰到问题， oh-my-zsh 无法升级， 具体提示如下：

```/Users/tao [tao@taodeMacBook-Air] [14:03]
> upgrade_oh_my_zsh
Upgrading Oh My Zsh
Cannot pull with rebase: You have unstaged changes.
Please commit or stash them.
There was an error updating. Try again later?
```

### 解决

解决方法如下：

```
cd ~/.oh-my-zsh/
git add .
git commit -m "commit message"
upgrade_oh_my_zsh
```
搞定， 提出如下 [以下是部分信息]

```
Hooray! Oh My Zsh has been updated and/or is at the current version.
To keep up on the latest news and updates, follow us on twitter: http://twitter.com/ohmyzsh
Get your Oh My Zsh swag at: http://shop.planetargon.com/
```

### 寻根

[oh-my-zsh github issue](https://github.com/robbyrussell/oh-my-zsh/issues/1991)

### 小技巧

.oh-my-zsh 这种类型的文件是隐藏文件， 直接 cd .oh-my-zsh 是进不去的。 
要加上 ~/
完整指令如下

```
cd ~/.oh-my-zsh/

```