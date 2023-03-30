# Python_BypassAV_demo

Python简单过360、火绒、腾讯管家的demo

> 其他的基本会被杀，微步沙箱/VT在线查杀基本都能查出来，本项目仅用来简单学习，测试国内几个杀软上线



### PyInstalle打包

```
安装pyinstaller库
pip install pyinstaller

简单打包
pyinstaller -F Python_BypassAV_demo.py

后台执行+ico打包
pyinstaller -F -w -i 98B8596E39.ico Python_BypassAV_demo.py
```

> 用nuitka的话效果会更好



![image-20230327171424455](C:\Users\Administrator\Desktop\Images\README\image-20230327171424455.png)

```
注意cobaltstrike生成的shellcode和脚本中shellcode的差异
快捷：\x替换成\\x
```

