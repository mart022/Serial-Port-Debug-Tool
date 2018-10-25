# 串口调试工具 Serial Port Debug Tool
基于C#和WPF的串口调试工具，实现了串口通信。

![Screenshot](https://raw.githubusercontent.com/dingzimin/Serial-Port-Debug-Tool/master/images/Screenshot0.png)

## 特性
* 支持基本的串口接收和发送
* 自动列出所有的串口
* 串口发生变化时，自动更新串口列表
* 支持自定义波特率、校验位、数据位、停止位
* 支持文本、16进制、带转义字符的文本
* 16进制可自由输入，支持包括但不限于以下格式
    * 024CB016EA
    * 02 4c b0 16 ea
    * 02-4C-B0-16-EA
    * 2 4CB0 16EA
    * z2y>.jt4cnm^#gB0']pok16rg-(=eA
* 支持ASCII、UTF-8编码，其他编码尚未实现
* 窗口置顶
* //窗口半透明
* 一键清空接收区数据
