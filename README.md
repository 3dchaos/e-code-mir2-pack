# e-code-mir2-pack
e语言程序，一键配置翎风引擎，并启动。并调起老登登录器
以下是本程序工作原理：
将翎风的配置文件 都打入易语言的图片资源表里，启动时候释放出来覆盖，把控制器和控制器配置器释放在C:\Users\用户名\AppData\Local\Temp\ld中，程序获取所在位置，重写配置文件，并启动控制器。监控进程，所有的服务都启动完毕后，调起客户端，如果没有提示
易语言版本为5.9 基础模块为精易模块，已上传。
原理：
![image](https://github.com/user-attachments/assets/846668f6-747c-49fd-b02d-f6304401a51e)
控制器，和配置文件存入资源中，配置文件中的路径要默认是 D:\MirServer
启动程序后 会释放资源中的配置文件，识别程序运行的目录，

![image](https://github.com/user-attachments/assets/cd3126c1-a7c5-4779-b22e-0fcc44fa8ece)
然后进行搜索替换。
![image](https://github.com/user-attachments/assets/c16e2cf2-aad7-4542-a0cc-5806348cdeab)
达到自动适配电脑任意位置的功能。
控制器台和控制台配置文件会释放在临时文件夹中并被重定义，达到隐藏控制台和控制台配置文件的功能。
启动过程中会有一个线程专门监视服务窗口是否全部启动
![image](https://github.com/user-attachments/assets/827eb389-ac08-427b-a1d8-7ad110c0f52e)

启动完毕后搜索是否有客户端，如果有就启动登录器
![image](https://github.com/user-attachments/assets/5306296a-7cbe-4754-b6de-d84f0489b5e8)
更新程序，在服务器中运行MD5生成器后，保存为一个INI文件

![image](https://github.com/user-attachments/assets/1b677e3d-ad20-4efc-944f-c905b68d5b77)
当点击程序更新时，会读取这个INI，并对比本地的文件的MD5 如果与服务器不一致，就会下载替换。
完成更新版本的功能
![image](https://github.com/user-attachments/assets/8976139d-43d4-4c20-94af-dec7ba1c34ae)
![image](https://github.com/user-attachments/assets/92c42771-7782-4b0f-b0fb-039c4e0e822b)
