# Basic ansible provision

```shell
pipenv shell
pipenv install

multipass-compose up

ansible-playbook -i instance-1.local, -u multipass-compose playbook.yaml

multipass-compose down
```
