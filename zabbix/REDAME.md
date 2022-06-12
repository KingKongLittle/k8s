
zabbix-mysql-statefullset.yaml
参考https://github.com/sosomasox/zabbix-on-k8s

1、修改了zabbix版本5.4
2、修改时区 "Asia/Shanghai"
3、replicas =1 

zabbix-mysql-deploy.yaml
参考：
https://github.com/jijeesh/k8s-zabbix
1、修改zabbix-web模块


kubectl apply -f postgresql-deploy.yaml -nzabbix
kubectl apply -f zabbix-postgresql-deploy.yaml  -nzabbix

使用postgresql参考代码 
1、https://github.com/CharcoGreen/k8s-zabbix/tree/main/zabbix
2、https://github.com/luis13byte/zabbix-server-k8s
