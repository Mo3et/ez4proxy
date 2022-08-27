# ez4proxy
Easy for WSL Terminals Proxy

# 规划
需要CLI生成工具  Cobra  和 Viper  

[Cobra使用教程](https://www.cnblogs.com/jiujuan/p/15487918.html)  

Example可以参考Caitouyun的 Client  看看使用了哪些工具  

需要Proxy的地方：
- shell
- git
- npm
- yarn
- pnpm

不同的Release 的package manager
- apt
- yum


## 分类
HTTP SockS5 unproxy init_proxy  Check_ip


## Todo List
- socks5 & http proxy with authentication.
- check whether the program exist before enable proxy for it
- proxy for sudo user (env_keep or sorts of things)
- proxy for:
	- yum
	- pip
	- gradle
	- git with ssh
	- gem
- no_proxy config
- learn some from arch wiki
