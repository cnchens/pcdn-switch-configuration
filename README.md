# pcdn-switch-configuration
PCDN交换机，开局配置，汇聚

# How to use/咋用
登录console，空配置的机器需要先设置密码 
然后直接复制粘贴文本即可 

# Port definition/端口定义
下联口（接光猫）： 
vlan从101开始，比如1号口的vlan就是101，2号口102，以此类推 

上联口（接服务器）： 
vlan从201开始，比如1号口的vlan就是201，2号口202 
默认所有的上联口的trunk allow-pass vlan都是全部下联口的vlan，部分设备不支持的会另行说明 
上联口有多个速率的，vlan会按照不同速率分组，比如10G口为2xx,40G口为3xx，100G口为4xx 

### 如果有其他改动都会在文件中单独说明
