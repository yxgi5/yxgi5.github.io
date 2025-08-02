# Welcome to My GitHub Pages

This page is a Navigtor of my github. 

近日失业赋闲在家, 稍微整理一下这个导航页吧, 分享一些可能能给别人启发的东西。

咱只有默念一句 mother fucker 给北京一男子.

## 操作系统维护流水帐

[my_os_log](https://github.com/yxgi5/my_os_log)

## makedeb

制作几个deb包
[makedeb](https://github.com/yxgi5/makedeb)

## 搭建机场
[0430bpb](https://github.com/yxgi5/0430bpb)

## ffmpeg

在windows和linux环境使用qsv或nvenc编码器进行降码率编码为hevc，MP4封包

[ffmpeg_bat_git](https://github.com/yxgi5/ffmpeg_bat_git)

## Schematic / PCB / qucs / Kicad ...

一个kicad工程
[FMC_bridge](https://github.com/yxgi5/FMC_bridge)

LPC2148核心板
[LPC214x_PACK](https://github.com/yxgi5/LPC214x_PACK)


## Scripts / Log / Utils / SQLite

几个爬虫. python + bash script, sqlite 作为数据库

1.这个主要就是增量式抓取 magnet 
[javbus_crawler](https://github.com/yxgi5/javbus_crawler_git)

2.这个呢主要就是抓取 sample images
[jav_lib](https://github.com/yxgi5/jav_lib)

3.做一个比较链接是否更新了的爬虫
[kkhai](https://github.com/yxgi5/kkhai_links_git)

4.mlocate / plocate 产生的db转换成sqlite数据库 用于查找多个硬盘内的文件
[locate_gen](https://github.com/yxgi5/locate_gen)

5.常用 bash 脚本
[usual_scripts](https://github.com/yxgi5/usual_scripts)

6.编译模板

[cmake_template](https://github.com/yxgi5/cmake_template)

[Makefile_template](https://github.com/yxgi5/Makefile_template)

[auto_version](https://github.com/yxgi5/auto_version)

## FPGA / IP / RTL / Sim

逐行扫描转隔行扫描
[video_interlacer](https://github.com/yxgi5/video_interlacer)

纯逻辑进行裁剪和扩展
[Artix7_image_crop_extend](https://github.com/yxgi5/Artix7_image_crop_extend)

DVP彩条发生器
[colorbar_gen](https://github.com/yxgi5/colorbar_gen)
[raw_colorbar_gen](https://github.com/yxgi5/raw_colorbar_gen)

### modbus_rtu_slave

纯FPGA实现modbus_rtu, 如果用软核就没有必要干这个. 或者后续做成 axi-lite 可配置
[modbus_rtu_slave](https://github.com/yxgi5/modbus_rtu_slave)

### NANEYE

NANEYE摄像头接入项目,输出DVP

[NANEYE_2D_IF](https://github.com/yxgi5/NANEYE_2D_IF)

[NANEYE_M_IF](https://github.com/yxgi5/NANEYE_M_IF)

[CONFIG_TX2](https://github.com/yxgi5/CONFIG_TX2)

### Zynq / Zynqmp

7系列纯FPGA的microblaze软核应用
[microblaze](https://github.com/yxgi5/microblaze)

安全IAP升级

[FPGA-SPI-Multiboot](https://github.com/yxgi5/FPGA-SPI-Multiboot)

[microblaze_golden_update](https://github.com/yxgi5/microblaze_golden_update)

[zynq_golden_update](https://github.com/yxgi5/zynq_golden_update)

[zynqmp_golden_update](https://github.com/yxgi5/zynqmp_golden_update)

共用模块bsp
[xilinx_common_bsp](https://github.com/yxgi5/xilinx_common_bsp)

创建单一vivado和vitis项目的模板
[vitis_template](https://github.com/yxgi5/vitis_template)

中断系统研究
[xilinx_soc_intr_system](https://github.com/yxgi5/xilinx_soc_intr_system)

### Video / Axi4 / Axis / HLS

外置 hdmi input 转为 dvp 输入
[it6801_demo](https://github.com/yxgi5/it6801_demo)

使用vivado自带视频有关ip的几个例子
[play_zynq](https://github.com/yxgi5/play_zynq)

### pcie

k325板子上使用pcie as endpoint
[k7_r5_pcie](https://github.com/yxgi5/k7_r5_pcie)

ps端的pcie endpoint
[ps_pcie_ep](https://github.com/yxgi5/ps_pcie_ep)

### 使用vivado IP 进行 HDMI / DP 输入 输出

[Hdmi_Passthrough](https://github.com/yxgi5/Hdmi_Passthrough)

[XCKU040_DP_test](https://github.com/yxgi5/XCKU040_DP_test)

### axis / HLS

结合ILA查看axis信号波形的IP
[axis_passthrough_monitor](https://github.com/yxgi5/axis_passthrough_monitor)

AXI_LITE总线上挂一组寄存器, 其中一个可以通过constant给PL这边作为版本信息, 其他的用处也可扩展为根据寄存器值切换电路逻辑等
[AXI_LITE_REG](https://github.com/yxgi5/AXI_LITE_REG)

用HLS实现IP
[rgb2bayer](https://github.com/yxgi5/rgb2bayer)

用HLS实现TPG
[axis_gen](https://github.com/yxgi5/axis_gen)

用HLS实现添加 embedded (top/bottom)行
[emb_gen](https://github.com/yxgi5/emb_gen)

用HLS实现竖方向采样
[vsampler](https://github.com/yxgi5/vsampler)

用于MIPI CSI输出的多vc mixer
[axis_4vc_mix](https://github.com/yxgi5/axis_4vc_mix)

MIPI CSI输入可能有多个VC用于拆分多个vc, 其实axis_switch用来做这个有不理想的地方, 所以做了这样的ip
[vc_slice](https://github.com/yxgi5/vc_slice)

[hls_debayer](https://github.com/yxgi5/hls_debayer)

[hls_bram_fifo](https://github.com/yxgi5/hls_bram_fifo)

非HLS实现缩小视频
[dresizer](https://github.com/yxgi5/dresizer)

研究 axis pipeline, 比如插入特定 latency 的图像处理算法, 这里来个简单的色彩空间转换
[rgb888_ycbcr](https://github.com/yxgi5/rgb888_ycbcr)

### 外设 IP

几个有点用处的IP
[i2c_ip](https://github.com/yxgi5/i2c_ip)

纯状态机实现 fake device
[i2c_slave](https://github.com/yxgi5/i2c_slave)

IO模拟i2c总线
[xgpio_i2c_and_emio_i2c](https://github.com/yxgi5/xgpio_i2c_and_emio_i2c)

i2c总线-FPGA-i2c总线, 相当于两边直通
[i2c_bypass_fpga](https://github.com/yxgi5/i2c_bypass_fpga)

## MCU / RTOS

qpc练手
[qpc_stm32f103ze-ek](https://github.com/yxgi5/qpc_stm32f103ze-ek)

从armfly移植过来BSP层面, 挺好用的
[stm32_v3_hal](https://github.com/yxgi5/stm32_v3_hal)
[v5_bsp_hal](https://github.com/yxgi5/v5_bsp_hal)

一个门禁卡项目
[idcard_access](https://github.com/yxgi5/idcard_access)

### Socket / Stack

下面几个纯为了给UDP通信增加可靠性

[udp-sliding-window-protocol-python](https://github.com/yxgi5/udp-sliding-window-protocol-python)

[kcp_echo](https://github.com/yxgi5/kcp_echo)

[lwip_kcp](https://github.com/yxgi5/lwip_kcp)


## SoC / Embeded System / V4L / MMP

[qt_osd_v4l2](https://github.com/yxgi5/qt_osd_v4l2)

[hi3556_proj](https://github.com/yxgi5/hi3556_proj)

[hi3556_mydoc](https://github.com/yxgi5/hi3556_mydoc)


### Kernel / Bootloader

[dm368_psplash](https://github.com/yxgi5/dm368_psplash)

[dm368_kernel](https://github.com/yxgi5/dm368_kernel)

[dm368_u-boot-src](https://github.com/yxgi5/dm368_u-boot-src)

[v4l_dm368](https://github.com/yxgi5/v4l_dm368)

[dm368_ubl-src](https://github.com/yxgi5/dm368_ubl-src)

### APUE

### Architect / Framework

## SoM / RPI ...

rk3588驱动及设备树修改

[rk3588_xx_board](https://github.com/yxgi5/rk3588_xx_board)

### rknn

[mnist_pytorch_rknn](https://github.com/yxgi5/mnist_pytorch_rknn)

[supercombo_rknn](https://github.com/yxgi5/supercombo_rknn)

### cuda

jetson nano

agx xavier

## Math / matlab / Maple ....

格式互转
[matlab_rgb_raw_conv](https://github.com/yxgi5/matlab_rgb_raw_conv)

PPM格式互转
[ppm-files](https://github.com/yxgi5/ppm-files)

### simulink


## Android

java

一个app项目
[CombustibleGas](https://github.com/yxgi5/CombustibleGas)

kotlin

