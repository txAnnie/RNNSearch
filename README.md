# RNNSearch
./run_shuffle.sh

./run_prepare.sh

安装Anaconda:
到官网http://continuum.io/downloads下载anaconda。 
选择linux64-bit-python2.7 
cd ~/Downloads
bash Anaconda-2.2.0-linux-x86_64.sh
输入Enter
浏览完后输入yes同意license agreement。 
最后，会提示你是否将anaconada的路径添加到Path中，这里我们输入yes： 
重新启动Terminal，我们会发现Python版本已经是anaconda的版本了，并且原有的python3没有受到任何影响，二者并行不备，各自独立地存在： 
python --version
python3 --version

安装Theano:
git clone http://github.com/Theano
cd Theano
python setup.py develop --user

安装feul:
git clone https://github.com/mila-udem/fuel
python setup.py install

./run_train.sh

./run_test.sh
