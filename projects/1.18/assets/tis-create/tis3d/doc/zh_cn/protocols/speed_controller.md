# 转速控制器
![我发誓它仍在控制之中……](block:create:rotation_speed_controller)

串口模块可以与转速控制器交互，以读写其目标转速。读取操作会返回其当前目标的RPM值。向它写入会用指定值覆写其目标的RPM值。试图读取大于32767的RPM值时，其行为由供应方指定的特定实现决定。