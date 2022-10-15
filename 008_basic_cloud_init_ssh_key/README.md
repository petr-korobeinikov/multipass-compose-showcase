# Basic ssh key auth example

```shell
ssh \
  -o StrictHostKeyChecking=no \
  -o UserKnownHostsFile=/dev/null \
  -i insecure_id_rsa \
    multipass-compose@instance-1.local
```
