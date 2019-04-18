# ansible-role-ntp
一个用于批量部署ntp-client的ansible的role
Ansible 版本为2+， role支持Centos6/7

## 配置
清单文件'hosts'应配置
```
[ntp]
192.168.123.168
```

##
执行
```bash
ansible-playbook -i hosts site.yml
```
