
# LAMP Stack deployment using ansible playbook

Deploy LAMP stack on Debian System with ansible playbook

## Getting Started

### Inventory

* Copy sample invetory file `inventory.ini.j2` to `inventory.ini` using `cp inventory.ini.j2 inventory.ini`
* Change `ansible_host` value with host IP
* Add ssh username to `ansible_user`

### Variables

* Copy sample variable file located in vars directory `defaults.yml.j2` to `defaults.yml` using `cp ./vars/defaults.yml.j2 ./vars/defaults.yml`
* set values based on your requirements


## Deployment

To deploy LAMP stack on debian system run

```bash
  ansible-playbook main.yml
```
append `-K` if ansible users needs sudo password to elevate sudo privileges


  
## License

[MIT](https://choosealicense.com/licenses/mit/)

  
## Authors

- [@kdpuvvadi](https://www.github.com/kdpuvvadi)

  
## 🔗 Links
[![twitter](https://img.shields.io/badge/twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/kdpuvvadi)

  