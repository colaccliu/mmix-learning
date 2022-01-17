###


tips：
- 根目录下的`mmix`和`mmixal`是mac版本的，其他的请前往官网下载（我也是在官网下载的嘿嘿
- 若无法跑，需要 chmod a+x filename(mmix或者mmixal)

### 开始
example写好之后，就如同使用GCC一样，先用mmixal汇编该源文件得到目标文件
    `mmixal -o hello hello.mms`
再将目标文件hello载入mmix模拟器即可
    `mmix hello`ß