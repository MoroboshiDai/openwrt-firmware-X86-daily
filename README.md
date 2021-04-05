每日同步构建x86 openwrt固件（lean源码） 下载位置在 Actions build中

Build x86 openwrt firmware (lean source code) synchronously daily. The download location is in Actions build.



#在上面本地编译时，当完成“配置完成后光标移动到 Save ，回车保存。”后，会在源码根目录生成一个 .config 文件，此时运行下面命令来提取配置差异，并保存在 diff.config 文件中备用：

#make defconfig
#./scripts/diffconfig.sh > diff.config   
# 将差异保存在 diff.config 文件中
