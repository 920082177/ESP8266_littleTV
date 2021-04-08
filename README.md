# ESP8266_littleTV
基于ESP8266的可充电天气小时钟  


压缩包里包含了程序、PCB和一些素材  
程序基于官方NONOS_SDK和安信可开发环境  
天气来源于心知天气，你可以去申请账号，替代我的账号，然后选择城市  
在user_main.c里修改WIFI信息  
低功耗问题一直没有解决，现在是每秒从时间服务器更新时间，可以改成间断性更新时间，然后用RTC时钟  

演示视频https://www.bilibili.com/video/BV1LT4y1A7YU/
