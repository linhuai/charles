# charles
charles 使用

### 一、 使用 charles 抓取 https 请求

1. 配置 Charles,允许抓取 https 包

   1.1 Proxy -> SSL Proxying Settings 

   1.2 勾选 Enable SSL Proxying 
   
   1.3 点击 【Add】 增加一个 location, Host: * (抓取所有 https 包)，Port: 443 (默认端口)

### 2. PC 端 Charles 安装 https 证书

Help -> SSL Proxying -> Install Charles Root Certificate 

### 3. 手机上下载并安装 Charles 证书

3.1 根据 Help->SSL Proxying -> Install Charles Root Certificate on Mobile Device or Remote Browser... 获得下载证书的地址（chls.pro/ssl）

3.2 下载完成后直接打开安装，或在 设置 -> 安全 里安装（不同手机操作不一样)

### 4. 手机设置代理

设置手机代理 Host 为 电脑IP， Port: 8888 (默认端口)


 
