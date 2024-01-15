## 1. 配置路径
/etc/NetworkManager/system-connections

修改完配置 `systemctl restart NetworkManager`

#### 1.1 kde界面创建的配置文件，手机连接会提示密码不对

修改wifi-security中的选项。

### 2. 连上了手机无法上网
1. 启用IP转发
2. 配置iptables进行流量转发