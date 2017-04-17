# nginx

*CentOS-7防火墙设置*

*查看80端口是否打开*
  
  firewall-cmd --query-port=80/tcp
  
*打开80端口*

  firewall-cmd --add-port=80/tcp
