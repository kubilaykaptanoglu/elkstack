# elkstack
Elasticsearch, logstash, kibana 6.2 Centos


### Ansible ExtraVars

kibanahost = kibana broadcast address e.g. (0.0.0.0)
elastichost = elasticsearch install node ip.. e.g. (localhost)
logpath = Log file path e.g.(/var/log/message)
logstashserver = installed logstash server ip

### Ansible Playbook command

```command
ansible-playbook elk6-2.yml -e "kibanahost=0.0.0.0" -e "elastichost=192.168.2.2" -e "logstashserver=192.168.2.2" -e "logpath=/var/log/messages"
```
