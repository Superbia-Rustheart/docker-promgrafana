# Installation

### Preprocessing
```bash
apt update -y
apt install docker -y
apt install docker.io -y
apt install docker-compose -y
apt install git -y
```

### Main processing
```bash
git clone https://github.com/Superbia-Rustheart/docker-promgrafana.git
cd docker-promgrafana
docker-compose up -d
```

### Unnecessary removing
```bash
cd .. && rm -r docker-promgrafana
```


# Next Up
### Check it out!
1. Go and check *loclhost:3000*
2. Use "admin" as login and password

### Make some safety
> [!CAUTION]
> 1. **Change password**
> 2. **Close ports** *9090* and *9093* on ur machine for external connections for security reasons
