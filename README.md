# P3P-download
最近看了某B站大佬做的“P3P光速下崽器”，就突然灵感涌现，做了个“P3P超光速下崽器”。
# 说明
主程序：《   P   3   P   超   光   速   下   崽   器   》.py
# 修复
若使用以后，任务管理器无法使用，请打开regedit.exe，定位到：
  HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Image File Execution Options
删除：taskmgr.exe taskkill.exe logoff.exe ntsd.exe shutdown.exe 这几个项
若找不到，请按F5，刷新一下，然后再删除！
