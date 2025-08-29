# noble_ppa
PPA Repo for DragonOS Noble

```
curl -s --compressed "https://alphafox02.github.io/noble_ppa/KEY.gpg" | gpg --dearmor | sudo tee /etc/apt/trusted.gpg.d/noble_ppa.gpg >/dev/null
sudo curl -s --compressed -o /etc/apt/sources.list.d/noble_ppa.list "https://alphafox02.github.io/noble_ppa/noble_ppa.list"
sudo apt update
```
