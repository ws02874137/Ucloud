## 如何搭建自己的HK VPS

购买vps看自己矿机数量和能力，最低配置即可，矿机流量很小，基本上1K一台的流量计算即可，比如你买1M的带宽，理论上可以带动1千台矿机，当时也最好给自己留点余量。
我推荐有十来台矿机的可以买下面的第二个1核2G/2M带宽，矿机数量超过100台建议购买第三个。Vps一定要购买HK的服务器，以防国外矿池全部进墙，这样买了国内vps也不能访问墙外矿池。

下面仅以Ucloud的vps为例子，其他vps请自行参考相关网站设置
- 通过以下链接可以注册：[点我注册](https://passport.ucloud.cn/?invitation_code=C1x00211FEE83A6)
```markdown
https://passport.ucloud.cn/?invitation_code=C1x00211FEE83A6
```
- 打开[ucloud网站](https://www.ucloud.cn/site/active/kuaijie.html?invitation_code=C1x00211FEE83A6E#xianggang)
```markdown
https://www.ucloud.cn/site/active/kuaijie.html?invitation_code=C1x00211FEE83A6E#xianggang
```
（感谢通过推广链接注册）
![Image](http://s-gz-416-dmgf-dl.oss.dogecdn.com/Ucloud/image001.png)

- 上面这个，个人建议直接购买1年或者3年，如果矿机多，选择第三个，新用户2M带宽一年费用是560块左右。
点击购买，下面以我自己购买的2核4G 2M带宽为例来说明。
选择个人新用户，选择1年/3年，点击购买，弹出如下：
![Image](http://s-gz-416-dmgf-dl.oss.dogecdn.com/Ucloud/image002.png)
- 注意选择HK地区，安装Windows/Windows 2019 64位，建议高配选择2M带宽，设置好自己的密码，点击立即支付，通过你自己的方式支付完成就购买成功了。

### 设置防火墙
购买完成之后，会提示进入控制台，你也可以登录之后自己打开控制台，控制台左边有两个图标，第一图标是你的主机，第二个图标是网络安全配置。
![Image](http://s-gz-416-dmgf-dl.oss.dogecdn.com/Ucloud/image003.png)
- 这样主机就算安装成功了，下面进行远程桌面连接，通过mstsc微软自带桌面连接，如下：
![Image](http://s-gz-416-dmgf-dl.oss.dogecdn.com/Ucloud/image004.png)
- 弹出这个对话框：
![Image](http://s-gz-416-dmgf-dl.oss.dogecdn.com/Ucloud/image005.png)
- 在这个对话框输入你的公网IP地址，如何查找公网IP地址（后面所有使用的IP地址都是这个），请到UC的网站这里查找：
![Image](http://s-gz-416-dmgf-dl.oss.dogecdn.com/Ucloud/image006.png)
- 输入公网IP地址后，弹出输入用户密码和口令对话框，用户输入账号administrator，密码是你在上面购买时候设置的密码，成功之后就远程登录到你购买的vps了。
![Image](http://s-gz-416-dmgf-dl.oss.dogecdn.com/Ucloud/image007.png)
- 然后就出现了远程桌面，远程桌面可以把本地文件拷贝，在远程桌面上直接粘贴。
![Image](http://s-gz-416-dmgf-dl.oss.dogecdn.com/Ucloud/image008.png)


Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](http://s-gz-416-dmgf-dl.oss.dogecdn.com/Ucloud/image001.png) and ![Image](src)
```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/ws02874137/Ucloud/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
