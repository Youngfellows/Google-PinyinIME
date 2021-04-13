### 简介
从源码中拿到的PinyinIME 输入法是没办法直接在Android Studio 中编译的，对于研究google 拼音
输入法来说很不方便。

所以，本项目是把源码中拼音输入法修改成了 gradle支持的项目，以便可以在Android Studio中研究。


原地址:[github.com/lizhangqu/PinyinIME](https://github.com/lizhangqu/PinyinIME)

### 改动
1. 项目目录改成 gradle 格式。
2. 添加 cmakelists 文件。
3. 使用LineageOS编译的framework.jar 替换SDK中的android.jar


### TODO
[ ] 适配最新的源码