# guitar-wireless-system
2.4g wireless audio transmit system

基于ESP32主控的无线音频收发器
音频接口使用WM8978
软包锂电供电
沉金+走线开窗+亚克力外壳（

主要功能
无线传输音频信号
typec充电
ap网页调整参数配置

附加功能
oled屏显示状态
主从机切换
多通道共用



第一版
RX
锂电池充放电管理 √
typec供电 √
typec usb esp 

音频芯片输入 
音频解码至esp i2s

esp接收充电信息
esp预留oled通信
esp供电 √
esp控制wm8978

