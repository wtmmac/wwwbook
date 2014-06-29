# Mercurial的安装

## linux
### pip安装

	sudo pip install mercurial

### 源码安装
~~~
wget http://mercurial.selenic.com/release/mercurial-3.0.1.tar.gz
tar zxvf  mercurial-3.0.1.tar.gz
cd  mercurial-3.0.1
python setup.py build
python setup.py install
#验证是否已安装
hg --version
~~~
## Windows
http://mercurial.selenic.com/release/windows/mercurial-3.0.1-x64.msi
http://mercurial.selenic.com/release/windows/mercurial-3.0.1-x86.msi
