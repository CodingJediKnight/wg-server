# wg-server

## Init
### Docker install
```bash
git clone https://github.com/docker/docker-install.git /tmp/docker-install
/tmp/docker-install/install.sh
/tmp/docker-install/rootless-install.sh install
sudo usermod -aG docker $USER
newgrp docker
```
### Config prepare
```bash
cp .env.example .env
vi .env
```
### How to generate password hash
https://github.com/wg-easy/wg-easy/blob/master/How_to_generate_an_bcrypt_hash.md

# References
* https://github.com/wg-easy/wg-easy