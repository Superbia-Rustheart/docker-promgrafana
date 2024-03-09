# Installation

### Via automation by bash
```bash
git clone https://gist.github.com/9e491678d90e0a9ac19e339230dc059a.git
cd 9e491678d90e0a9ac19e339230dc059a
bash docker-promgrafana-install.sh
```

### Or via half-manual mode
```bash
apt update -y
apt install docker -y
apt install docker.io -y
apt install docker-compose -y
apt install git -y
git clone https://github.com/Superbia-Rustheart/docker-promgrafana.git
cd docker-promgrafana
chmod +x inst.sh
docker-compose up -d
```

# Next Up
> [!IMPORTANT]
> 123
1. Go and check *loclhost:3000*
2. Use "admin" as login and password
3. **Change password**
4. **Close ports** *9090* and *9093* on ur machine for external connections for **security** reasons
5. Delete the files remaining after installation
