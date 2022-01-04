## Creating mysql cluster with 3 nodes in Debian 10 Buster </br>
Modify addresses to `inventory/inventory.yml` </br>
Modify addresses and hostname in `templates/*.j2` </br>
Modify hosts name in `play.yml` </br>

Result after `ansible-playbook play.yml -i inventory/inventory.yml`: </br>
![](https://github.com/murzinvit/screen_1/blob/c2bd1f960ffa129582f97e1791e29057377b9527/Mysql_screen_cluster.jpg) </br>


