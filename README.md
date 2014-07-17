android-app-pack
================

auto pack android app through ant


1.用法：

    a.  把custom_build.xml复制到工程的跟目录。
 
    b.  把本目录的路径放到PATH中。(Linux和Mac用户你懂的)，如果是windows用户，俺也不管了。

    c.  在工程根目录或者指定工程目录执行android-app-pack。譬如 ~/xxx: android-app-pack 或者 android-app-pack ~/xxx


2.
    a.友盟多渠道打包：
    
        在根目录里面，创建一个"pack.config"文件。有几个channel就创建几条channel=xxx（xxx表示channel name）

        例如：
      
        channel=91
        channel=Tencent
        channel=WanDouJia
        channel=360
        channel=XiaoMi
        channel=163
        channel=daXiangCe      

    b.如果在使用的过程中出现了。invalid resource blablabla之类的。然后以bin/res/crunch结尾的，请删除之。

   


注：
    custom_build.xml参考了 https://github.com/sinkcup/AntDemo 在此表示感谢
 
