# DeepLearning
2학년 1학기 DeepLearningⅠ

### User#1 : HyeJinKyu's Desktop
 - git config --global user.name "HyeJinKyu's Desktop"

### User#2 : HyeJinKyu's Galaxy360
 - git config --global user.name "HyeJinKyu's Galaxy360"

### User#3 : JinKyu's InternetPC
 - git config --global user.name "JinKyu's InternetPC"

### User#4 : HyeJinKyu's MacBook Pro14
 - git config --global user.name "HyeJinKyu's MacBookPro14"


# 2024.03.21
## Python
 - Current Version : 3.12.2
 - Install Version : 3.9.13(2024.05.17, pip 22.0.4) -> 3.9.19(2024.03.19) Security Fix
 - TensorFlow : Python 3.6 ~ 3.9 지원(Pip 19.0 이상)

## TensorFlow
 - pip install tensorflow==2.15.0
 - pip install matplotlib
 -
 -

## Keras
 - Current Version : 3.0.0
 - Google Colab Version : 2.15.0
 - Backend : JAX, TensorFlow, Pytorch
 - 3.0.0, 2.15.0 : TensorFlow 2.15.0 호환
 - pip install keras==2.15.0 => 설치
 - CUDA : 
 - cuDNN : 8.1

## Pip
 - pip list
 - pip install --upgrade pip (pip 24.0)
 - pip --version

## VirtualEnv
 - pip install virtualenv

# 2024.03.26
## Local
 #### Windows Native
 - https://www.tensorflow.org/install/pip?hl=ko#windows-native_1

 #### MiniConda(Python 3.9)
 - https://docs.anaconda.com/free/miniconda/miniconda-other-installer-links
 - > conda create --name TensorFlow-GPU python=3.9
 - > conda deactivate
 - > conda activate TensorFlow-GPU
 - > conda install -c conda-forge cudatoolkit=11.2 cudnn=8.1.0
 - > pip install --upgrade pip
 - > pip install "tensorflow<2.11"

 #### CUDA(GPU) 확인
 - > python -c "import tensorflow as tf; print(tf.reduce_sum(tf.random.normal([1000, 1000])))"
 - > python -c "import tensorflow as tf; print(tf.config.list_physical_devices('GPU'))"

 #### Environment Version
 - > Python > !python -V : Python 3.9.19
 - > Pip > !pip -V : pip 24.0 (python 3.9)
 - > TensorFlow > import tensorflow as tf;print(tf.__version__); : 2.10.1
 - > Keras > import keras;print(keras.__version__); : 2.10.0
 - > CUDA > conda list cudatoolkit : 11.2.2(h7d7167e_13)

## Google Colab
 - > Python > !python -V : Python 3.10.12
 - > Pip > !pip -V : pip 23.1.2 from /usr/local/lib/python3.10/dist-packages/pip (python 3.10)
 - > TensorFlow > import tensorflow as tf;print(tf.__version__); : 2.15.0
 - > Keras > import keras;print(keras.__version__); : 2.15.0
 - > CUDA > !nvcc --version : V12.2.140(33191640_0)
 
 
