### Скачайте датасет и объедините за 2007 год в папку 2007, а за 2012 в 2012 соответственно.
[Вот ссылочка на датасет]().

### Скачайте [checkpoint](https://mega.nz/file/x09iGLYB#U-nxmoh4-x5K2Ftq-XKjB1WwgW8fS1fynjSDcWjkU88). 
Его надо еще обучать, тк до сих пор в некотрых местах работает некоректно.

### Для того, чтоб все работало вам надо установить PyTorch под свой конфиг (но нужно выбрать CUDA 11.8 для удобства).
https://pytorch.org/get-started/locally/
![image](https://github.com/NoonLicht/base/assets/121355541/25a12112-f2ff-4df9-9e87-d90d94e61ad7)

Не забудьте еще установить CUDAToolKit 
```
pip install cudatoolkit=11.8
```
Еще вам надо будет скачать [cuDNN](https://developer.nvidia.com/cudnn) тоже под CUDA 11.8.
