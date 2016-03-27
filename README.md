# SublimeText-IM-Fix
包含修复sublime text中文输入的共享库，以及对应修改后的subl链接文件和desktop文件

### 使用方法

这里以Ubuntu系统为例来说明，假设sublime text安装在了**/opt/**下。

1. git clone https://github.com/smslit/SublimeText-IM-Fix.git && cd SublimeText-IM-Fix
2. sudo cp lib/libsublime-imfix.so /opt/sublime_text
3. sudo cp bin/subl /usr/bin 
4. sudo cp applications/sublime_text.desktop /usr/share/applications/

### 检查

1. 命令行下：subl，打开sublime text如果操作正确的话支持中文输入了
2. launcher找到sublime text，单击运行，如果正常的话也支持中文输入了。
