# Basic multimachine with cloud-init

```shell
multipass-compose up

multipass exec web-server -- cat /tmp/role.txt
multipass exec database -- cat /tmp/role.txt
multipass exec backend -- cat /tmp/role.txt

multipass-compose down
```
