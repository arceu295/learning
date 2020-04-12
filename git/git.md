Git
=======
> ssh -vvv git@github.com

Check IdenityFile for github
(git is user on config)

> ...

File ~/.ssh/config
```
Host github.com
  Hostname github.com
  User git
  IdentityFile ~/.ssh/id_rsa_arceu295
  IdentitiesOnly yes
```
Grant permission for file config
```shell
sudo chmod 644 ~/.ssh/config
```
```
ssh-add -l
ssh-add ~/.ssh/id_rsa_arceu295
```
