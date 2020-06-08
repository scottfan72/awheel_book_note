# GIT 复习笔记

### 工欲善其事,必先利其器

Linux平台Git图形化管理工具: **GitAhead**

安装过程:

1. 从GitHub上搜索GitAhead下载适用于Linux系统的 `.sh` 格式的安装文件.

2. 将安装文件拷贝到用户家目录下,然后赋予其执行权限,运行脚本文件,按照提示安装即可.

3. 在我刚使用此软件时,我发现 `(Fcitx框架)中文输入法` 无法使用,我想可能是GitAhead输入法上下文切换动态链接库的问题

   于是,我把系统目录下的动态链接库拷贝到了GitAhead根目录下 `Plugins` 的 `platforminputcontexts` 文件夹中,使用的命令如下

   ```bash
   sudo cp /usr/lib/x86_64-linux-gnu/qt5/plugins/platforminputcontexts/libfcitxplatforminputcontextplugin.so ~/GitAhead/Plugins/platforminputcontexts/
   ```

这样我Linux中Git GUI工具就准备好了.

### 好记性不如烂笔头

