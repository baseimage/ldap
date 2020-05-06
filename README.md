## install openldap in apline 3.10

### run docker build
```shell
docker build -t openldap:2.4.50 .
```
### run docker container
link docker-compose

```
docker-compose -f ldap.yaml up -d
```
