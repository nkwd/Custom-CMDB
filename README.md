# roncoo-cmdb
龙果学院推出开源运维平台，目前版本实现：权限控制，CMDB,cobbler装机平台，zabbix管理平台<br />
后期会持续推出发布平台，批量管理平台、希望跟大家交流学习
功能说明：

相关视频地址：http://www.roncoo.com/course/view/a2d58fe08172447696412fb7af1de620

  一、装机平台：基于cobbler来做二次开发.


    平台指定安装操作系统版本镜像，安装的分区规划。当然定制ks文件这一块可以随机修改。

     通过厂商MAC地址，指定IP,MAC,网关等，通过管理平台指定IP和系统版本之后，机房相关人员插上网线开机即可安装。

     记录操作数据。


  二、用户权限管理：


       可以对用户进行管理，对用户增删改查修改密码等。

     用户组权限，角色管理。


  三、CMDB管理：


       机房，机柜的相关管理增删改查，这一块只有admin用户可以查看和修改。

     脚本采集系统硬件数据，通过API方式提交和人工录入的半自动方式。

     数据收集参数和删除。


  四、zabbix管理：


     通过CMDB平台联动到zabbix数据库。

     实现对zabbix主机的批量模板绑定、删除；基本上已经完成zabbix管理工作。

     主机出现问题，或者维护数据时候添加维护周期。

     调用zabbix图形在运维平台展示
     
  五、系统保障处理:
