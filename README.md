# InstallTensorsFlow
## 环境
- Windows 10
installTensorsFlow- Anaconda 3.X
- Python > 3.5.64

### Trensorflow 安装(CPU版本)
1 Anacoda 安装 windows版本 [Anacoda](https://www.anaconda.com/download/) **安装过程不语累述**
2 Trensorflow 安装
  - 在Anacoda中创建一个虚拟环境(Trensorflow): conda create -n tensorflow python=3.6.3
  - 运行 开始菜单->Anaconda3 ->Anaconda Navigator -> 点击 Enviroments, 可以看到tensorflow环境已经创建完毕
  - 激活虚拟环境: activate tensorflow
  - 关闭虚拟环境: deactivate tensorflow
  - 在虚拟环境中安装cpu版本的Tensorsflow: pip install --upgrade --ignore-installed tensorflow
  **此版本是CPU版本,如有想安装GPU版本请自行Google**
  - 测试Tensorflow
   ``` 
  import tensorflow as tf
  hello = tf.constant('Hello, World! Tensorflow!')
  sess = tf.Session()
  print(sess.run(hello))
   ``` 
