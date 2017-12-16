# InstallTensorsFlow
## Setting
- Windows 10
- Anaconda 3.X
- Python > 3.5.64

### Trensorflow install step(CPU Version)
1 Anacoda installin windows [Anacoda](https://www.anaconda.com/download/) **if you do not konw, how to install anaconda into your PC, you can google it**
2 Trensorflow install
  - ***Create a virtual environment in Anacoda(Trensorflow)***: conda create -n tensorflow python=3.6.3
  - ***Run the Start menu*** ->Anaconda3 ->Anaconda Navigator -> clik Enviroments, You can see that the tensorflow environment has been created
  - ***Activate the virtual environment***: activate tensorflow
  - ***Deactivate the virtual environment***: deactivate tensorflow
  - ***Install cpu version of Tensorsflow in virtual environment***: pip install --upgrade --ignore-installed tensorflow
  
  **This version is the CPU version, if you want to install the GPU version of your own Google**
  - ***Test***
   ``` 
  import tensorflow as tf
  hello = tf.constant('Hello, World! Tensorflow!')
  sess = tf.Session()
  print(sess.run(hello))
   ``` 



## 环境
- Windows 10
installTensorsFlow- Anaconda 3.X
- Python > 3.5.64

### Trensorflow 安装(CPU版本)
1 Anacoda 安装 windows版本 [Anacoda](https://www.anaconda.com/download/) **安装过程不语累述**
2 Trensorflow 安装
  - ***在Anacoda中创建一个虚拟环境(Trensorflow)***: conda create -n tensorflow python=3.6.3
  - ***运行 开始菜单***->Anaconda3 ->Anaconda Navigator -> 点击 Enviroments, 可以看到tensorflow环境已经创建完毕
  - ***激活虚拟环境***: activate tensorflow
  - ***关闭虚拟环境***: deactivate tensorflow
  - ***在虚拟环境中安装cpu版本的Tensorsflow***: pip install --upgrade --ignore-installed tensorflow
  
  **此版本是CPU版本,如有想安装GPU版本请自行Google**
  - ***测试Tensorflow是否安装成功***
   ``` 
  import tensorflow as tf
  hello = tf.constant('Hello, World! Tensorflow!')
  sess = tf.Session()
  print(sess.run(hello))
   ``` 
