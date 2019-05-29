# curve-qwt-com-thread

![curve-GUI.jpg](https://github.com/Aslm/curve-qwt-com-thread/blob/master/curve-GUI.jpg)
![serial-GUI.jpg](https://github.com/Aslm/curve-qwt-com-thread/blob/master/serial-GUI.jpg)
![about-GUI.png](https://github.com/Aslm/curve-qwt-com-thread/blob/master/about-GUI.png)

/**
*********************************************************************************************************
*
*	@ProjectName : curve-qwt-com-thread
*	@Description : 
*	@Version     : V1.0
*	@Description : 
*
*	....................Update....................
*	@Version  @Date      @Design   @Description
*    V1.0    2016.11.23  Aslm       demo
*
* @ME:sillyman2008@outlook.com
*********************************************************************************************************/

**********************************
1、实时解析串口数据并绘制相关曲线 \<br>  
2、串口以及数据处理单独一个进程（不影响GUI刷新) \<br>   
3、曲线、串口参数可配置、可保存 \<br>  
4、log记录 \<br>  
5、win release版本已经发布 <br/>
6、可在 linux 下编译发布  <br/>
7、可用于 速度、温度、加速度、陀螺仪等 数据实时采集 <br/>

**********************************
1、曲线配置 颜色、名称 等参数时要先点击 set按钮，然后再点击 reset按钮 开启重新绘制 \<br>  
2、参数保存请按 cfgSave按钮 \<br>  
3、串口数据格式请参考 <下位机发送格式Demo.c> \<br>  
4、如果使用单片机与软件通讯，请选用较好的 串口转usb设备 ，如 CP21X ； \<br>  
   不然会因为速率不够而导致数据解析会经常报错 \<br>  

**********************************
1、../cfg 文件夹 为配置文件 \<br>  
2、../log 文件夹 记录log \<br>  

**********************************
1、曲线绘制基于 qwt控件 \<br>  
2、串口控制基于 qextserial类 \<br>  

**********************************
感谢 Qt开源社区 www.qter.org \<br>  
本程序 串口部分 参考了社区的 qcom 1.1 \<br>  
1、由于本人是机器人相关行业，由于工作上的需求，后续会在该版本上添加相关的控制函数 <br/>
   用于发送指定的数据指令与其他硬件交互。<br/>
2、欢迎点星星 <手动笑脸> <br/>
