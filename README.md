docker-full
===========

Full stack web docker image build

Using:


```
sudo docker run -v ~/devel:/devel -p 3000:3000 -p 8080:8080 -p 9000:9000 -p 35729:35729 -p 2222:22 -t kossoy/docker-full
cat ~/.ssh/id_rsa.pub | ssh -p 2222 devel@localhost 'mkdir ~/.ssh && cat >> ~/.ssh/authorized_keys'

```
