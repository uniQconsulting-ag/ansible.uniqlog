Check Services:
- `systemctl status graylog-server elasticsearch mongod nginx`

Elasticsearch Overview:
- `curl -s -XGET http://localhost:9200/_cat/indices?v ; echo xxxxxxxxxxxxxxxx ; curl -s -XGET http://localhost:9200/_cat/aliases?v`

Graylog Config:
 `/etc/graylog/server/server.conf`
 `/etc/sysconfig/graylog-server`