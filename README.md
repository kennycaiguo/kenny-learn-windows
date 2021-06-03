windows 问题
# 如何虚拟化物理机？
答：
1.下载Microsoft的Disk2vhd_v2.01工具
2.运行disk2vhd.exe
3.需要将镜像文件保存到一个usb硬盘，容量比物理机的硬盘要大
完成后，生成两个文件如：WIN-5OKFMRREPRH-0.VHDX和WIN-5OKFMRREPRH-1.VHDX
4.这两个文件VMware使用不了，需要virtualBox虚拟机的一个叫VBoxManage.exe的工具将其转换为vmdk文件
5.端口VMware，创建一个新虚拟机，选择使用现有磁盘，将上面转换的vmdk磁盘导入，就可以将物理机转换为虚拟机了。
# <a href="https://blog.csdn.net/flower4wine/article/details/17150055"> win7安装了vs2010后安装DXSDK_jun10失败</a>

# <a href="http://blog.sina.com.cn/s/blog_3f61a3230102x7hs.html">emule电驴无法连接服务器</a>

# <a href="https://answers.microsoft.com/zh-hans/windows/forum/windows_10-windows_store/windowsapps%E6%AF%8F%E9%9A%9415%E5%88%86%E9%90%98/93298795-a75c-457d-81bf-ddbbad8a135b">WindowsApps每隔15分鐘就會跳一次参数错误信息</a>
