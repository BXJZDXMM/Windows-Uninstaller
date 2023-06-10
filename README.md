# Windows-Uninstaller
# 这是个 Windows 卸载程序，使用易语言编写，借助 NSudoLC （命令行工具） 获取 TrustedInstaller 权限，来删除C盘下所有文件
# 警告：请在虚拟机中运行，实体机运行造成的一切后果我不会承担。
# 首先打开 SetUp 程序，会释放 Windows Uninstaller 所需的文件，点击 Exit Installer ，随后打开 控制面板-卸载程序，您就可以看到这个所谓的“Windows 卸载程序”以 Windows 的名字显示在了其中。双击打开，点击按钮，点击两次确定，Windows 就会开始卸载。
# 稍等片刻，您的桌面会变黑、无法打开任何程序、Explorer 崩溃、无法使用 CAD 快捷键…… 断电（注意是断电，不是关机再打开，因为您这时无法通过系统的关机方法来关机。）重启后会自动进入修复模式。
# 这个程序因为结构过于简单，不公开源码。
