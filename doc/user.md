```shell
table user

user_id
password
real_name
nick_name
mail
phone
address
avtar
creater_user
create_time
update_time
delete_flag

```
```shell
table user_auth

id
user_id
auth_id
```
```shell
table token 

id
user_id
access_token
refresh_token
expire_time
```
```shell
table auth
auth_id
auth_group_name
auth_description
creater
```
```shell
table login_log
id
user_id
ip
mac
login_time
```
