# Checkpoints

* aws instance
* sokrates ssh
* hosts.ini

```bash
eval `ssh-agent`
ssh-add ~/.ssh/id_student
ssh-add {sciezka do klucza}
```
* vouchershop.jar // public access

## to


- [X] ssh access
- [X] install java runtime env
    - https://corretto.aws/downloads/latest/amazon-corretto-11-x64-al2-jre.rpm
- [X] download jar
    - https://github.com/jkanclerz/vouchershop-N3511/releases/download/v0.2/vouchershop.jar
- [X] java -jar app.jar --server.port=8080
- [X] define dir structure
- [X] create user

- [X] setup as background service
- [X] start on boot

- [ ] automate via ansible

### 11:15

## todo

- install app_nodes

- [ ] EPEL REPO
- [ ] install nginx
- [ ] configure proyx to app node
- [ ] declare installation via ansible
- [ ] reconfigure proxy -> lb 
- [ ] add 1 more app node
- [ ] test lb settings