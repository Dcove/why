# why
[![Version](https://img.shields.io/badge/Release-1.2preview%20public3-red.svg)](https://github.com/dcove/why/releases/tag/1.2preview-pub3)
[![LICENSE](https://img.shields.io/badge/License-GPL3.0-blue.svg)](http://www.gnu.org/licenses/gpl-3.0.html)
[![ISSUES](https://img.shields.io/github/issues/dcove/why)](https://github.com/Dcove/why/pull)
[![FORKS](https://img.shields.io/github/forks/dcove/why)](https://github.com/Dcove/why/)
[![STARS](https://img.shields.io/github/stars/dcove/why)](https://github.com/Dcove/why/)
<a href="https://github.com/purofle"><img src="https://img.shields.io/badge/Based%20on-purofle%2Fwhy-green.svg" /></a>

Termux下的多功能工具箱
## 安装
### 安装方法1：
```bash
# 需要git
git clone https://github.com/Dcove/why.git ~/why/
bash ~/why/install.sh
```
### 安装方法2：
```bash
# 需要wget
wget https://raw.githubusercontent.com/Dcove/why/master/why -O $PREFIX/bin/why
chmod +x $PREFIX/bin/why
```
### 安装方法3：
1. 打开[Releases](https://github.com/Dcove/why/releases)
2. 下载Deb文件（使用Termux请下载以Termux结尾的，且下面的命令不要加上sudo;使用Ubuntu、LinuxMint、Deepin、Debian等请下载debian，并加上sudo）
3. `(sudo) dpkg -i newwhy_*_*.deb`
---

### 功能使用
BiliBiliHelper:  
等待代码跑完后，会自动进入编辑页面，使用i编辑，使用ESC+ZZ进行保存

---

###### 版权声明
> 本项目由[GitHub @purofle](https://github.com/purofle)制作，后原作者将该项目转至开发不开源的python工具箱`xom-and-why`中  
> 现在我根据之前为对该项目Pull Request时的fork来重建该项目.  
> **本项目遵循 GNU PUBLIC LICENSE3.0 协议开源**
  
*HEXO安装部分的源代码来自QAZS，QAZS采用MPL开源，作者Dcove*  
你可以使用`git clone https://e.coding.net/dcove/qazs/smux.git`克隆qazs（smux是其原名）
