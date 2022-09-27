# twrp_device_Z01
A TWRP device tree for Gionee Z01.
本device tree使用[twrpdtgen](https://github.com/twrpdtgen/twrpdtgen)生成。
[点击访问可以使用repo工具的TWRP源码项目](https://github.com/minimal-manifest-twrp)
## 克隆代码
先cd到TWRP源码目录。然后运行
```sh
apt install git
```
```sh
git clone https://github.com/twrpdtgen/twrpdtgen.git
```
克隆。
## 使用此DT构建
```sh
mv ./unknown ./device
```
```sh
source build/envsetup.sh
```
```sh
lunch omni_Z01-eng
```
```sh
mka recoveryimage
```
