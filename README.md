# jump-jump
微信跳一跳辅助


思路和原理参考 https://github.com/wangshub/wechat_jump_game 自动跳跃算法细节参考

本项目只支持 iOS

操作步骤：
1. 需要在 Mac 上安装配置 WebDriverAgent，参考[教程](https://testerhome.com/topics/7220)
2. 在手机上运行WDA，打印出‘ServerURLHere->http://10.67.52.240:8100<-ServerURLHere’这样的日志
3. WDA配置完成后，在命令行里进入项目文件目录， 执行 chmod 775 ./youjumpijump-ios && ./youjumpijump-ios，然后根据提示输入打印出的ip和端口，经测试，系数设置为2跑的分数比较理想。

注意：在执行命令行里系数命令时，先运行跳一跳。
