# Actions-Lean-OpenWrt

[使用 GitHub Actions 云编译 OpenWrt](https://p3terx.com/archives/build-openwrt-with-github-actions.html)

## Usage

- 源码：[Lean's OpenWrt](https://github.com/coolsnowwolf/lede)

- [Lede 的 Applications 插件应用说明](https://www.right.com.cn/forum/thread-344825-1-1.html)

- 修改自定义参数文件：`diy-part1.sh` ，`diy-part2.sh`


## 开始创建任务编译 
actions -> Build OpenWrt -> Run workflow -> True -> Run workflow


## 自动编译

- 上传或更改 `.config` 配置文件，自动编译

## or SSH连接编译

- SSH connection to Actions 复制SSH连接，黑屏按Ctrl + C，输入：cd openwrt && make menuconfig


