# caffe-rgh
- 支持deeplab
- matread matwrite层
- liuwei的ParseNet和商汤的PSPNet
# 编译matio
由于使用了matread和matwrite需要编译下matio
下载: https://sourceforge.net/projects/matio/files/latest/download?source=files
编译:
```sh
tar zxf matio-X.Y.Z.tar.gz
cd matio-X.Y.Z
sudo sh ./configure
make
# make check
sudo make install
```
# 编译
- make -j32 (有可能出错, 若出错make clean后改成make -j16)
- make pycaffe

# 使用

[在我们的数据集上训练(带光流)](https://github.com/Sundrops/caffe-rgh/tree/master/examples/train_our_dataset)
