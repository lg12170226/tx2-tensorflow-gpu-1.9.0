tensorflow_gpu-1.9.0+nv18.8-cp35-cp35m-linux_aarch64.whl

1.require： python3.5

2.install pip3 and upgrade
  install:   sudo apt-get install python3-pip
  update :   pip3 install --upgrade pip  
          if err try:
             sudo pip3 install --upgrade pip -vv
             
3.install tensorflow_gpu-1.9.0
  i   cd path to tensorflow_gpu-1.9.0+nv18.8-cp35-cp35m-linux_aarch64.whl
  ii  pip3 install tensorflow_gpu-1.9.0+nv18.8-cp35-cp35m-linux_aarch64.whl
  
4 ERR 
    RuntimeError: module compiled against API version 0xc but this version of numpy is 0xa
  solve:
    sudo pip3 install numpy --upgrade
  
  
reference : https://blog.csdn.net/qq_40708778/article/details/88096907#commentBox
