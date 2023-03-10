# iMoo-Toolkit使用教程

- ⚠此教程会涉及到部分专有名词，我会选择一部分解释，如果没有，请自行搜索。
- ⚠此软件基于**adb**，请确保后台没有其他**adb**运行，否则会导致无法连接。

接下来会对每个功能分别进行详细的讲解:
 - ⚠是每个功能分别讲解！不是步骤！其次下面的路径，链接均为例子，只是告诉你该这么写而不是让你复制进去！
 1. 安装设备(手表)的内部存储根目录`/sdcard/`下的所有apk文件。
    - 文件名请根据`1.apk`,`2.apk`这样排列。
    - ⚠不推荐新手小白使用
 2. 安装设备(手表)内特定(绝对)路径的文件，如`/sdcard/Magisk-v23.1.apk`。
    - ⚠不推荐新手小白使用
 3. 解锁`adb push`的限制以可以使用其将文件传输至设备(手表)。
 4. 从本地(电脑)或网络安装软件。
    - 从本地可以使用绝对路径和相对路径，如`C:\User\Administrator\Download\Magisk-v23.0.apk`。
    - 从网络安装输入链接即可，如`https://github.com/topjohnwu/Magisk/releases/download/v23.0/Magisk-v23.0.apk`
    - 如果你看不懂，可以直接向你要安装的本地文件或文件链接拖入窗口即可。
    - ♥️推荐新手小白使用♥️

- ⚠关于非法安装：
    1. 使用权限不高的可卸载软件的软件卸载名为「手表」`com.xtc.i3launcher`的系统桌面的更新;
        - 桌面，启动器是同一种东西。
        - 不要卸载软件本身，否则会变砖。
    2. 然后会黑屏，随后手动重启进系统；
        - 进不去系统就砖了。
    3. 安装第三方桌面，使用第三方启动器打开软件即可。

- 根据部分~~九年教育的漏网之鱼~~小白反馈，它们看不懂以上教程，因此以下将根据一般用户的最低需求（解push，安装电脑上的安装包）进行一步到位的讲解：
    - 手表打开`adb`用四点线链接电脑，打开软件，点**3**，回车，重启手表，重连，打开软件，点**4**，回车，将你要安装的软件的安装包拖进去，回车，完成安装。
    - 安装mt管理器，打开，点击左上角打开侧边栏，下滑，找到工具，点击展开，打开提取安装包，找到「手表」，点击更多，卸载，随后报错，重启，重新连接电脑，安装小天才启动器，打开，打开原来有非法安装的应用，打开成功，非法安装解除，随后禁用自动更新。
        - 安装不了小天才启动器请卸载粤康码。
