# grafana_dashboard


Those Dashboard requires an alias set on hosts.

For example : 
```
      - targets: ['127.0.0.1:9100']
        labels:
          alias: localhost
``` 

Graph will used those aliases to group by. 
