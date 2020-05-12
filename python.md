# python 環境設定
### [Homebrew](https://brew.sh/index_zh-tw) 套件管理工具
> /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
- Homebrew 檔案位置
>$ cd /usr/local  
$ find Cellar  
Cellar/wget/1.16.1  
Cellar/wget/1.16.1/bin/wget  
Cellar/wget/1.16.1/share/man/man1/wget.1  
$ ls -l bin  
bin/wget -> ../Cellar/wget/1.16.1/bin/wget  
- Homebrew package
>$ brew create https://foo.com/bar-1.0.tgz  
Created /usr/local/Homebrew/Library/Taps/homebrew/homebrew-core/Formula/bar.rb

---
安裝 python
> brew install python3


安裝 ipython3
>pip3 insatll ipython

extra modules to run ipython notebook
>pip3 install pyzmq  
>pip3 install jaija2  
>pip3 install tornado

run notebook
>ipython3 notebook
---
虛擬環境的選擇 >>> [virtualenv](https://www.maxlist.xyz/2020/04/01/python-pyenv-virtualenv/)
安裝 virtualenv
> pip3 install virtualenv


參考網站  
1.[pyenv&virtualenv](https://codertw.com/程式語言/471323/)  
2.[pyenv&virtualenv](https://www.maxlist.xyz/2020/04/01/python-pyenv-virtualenv/)
3.[100天](https://github.com/jackfrued/Python-100-Days/tree/master/Day01-15/res)
