# Huawei_theme_package_utils_v9.x
华为主题包制作-工具集合

环境条件：
python27
~~7z（压缩hwt包用，打包文件压缩格式有问题，已改用gunwin32中的zip unzip 支持）~~
gunwin32 bin目录添加到path环境变量

1.windows 下安装choco
cmd下:
@"%SystemRoot%\System32\WindowsPowerShell\v1.0\powershell.exe" -NoProfile -InputFormat None -ExecutionPolicy Bypass -Command "iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))" && SET "PATH=%PATH%;%ALLUSERSPROFILE%\chocolatey\bin"


2.choco安装python2.7

~~3.choco安装7z~~

4.choco安装pip

5.pip 修改国内源

打包：
界面编辑处理完毕的主题包文件夹   
放至theme_nopackage 文件夹
点击 打包.bat 运行 
生成的hwt文件在theme_package文件夹下

解包：
hwt文件放置到theme_package文件夹下 ，
点击 解包.bat 运行
生成的文件夹放置在 theme_nopackage 文件夹下

TODO：
测试工具
