# Installing PostgreSQL on Linux

## Command lines

reference: [https://learn.microsoft.com/en-us/windows/wsl/tutorials/wsl-database]

### 1 Installation

```sh
sudo apt update
sudo apt install postgresql postgresql-contrib
```

Check the command if avialable

```sh
psql --version
```

### Start and Stop PSQL service

Start or Stop
```sh
sudo service postgresql start
sudo service postgresql stop 
```

Check status
```sh
sudo service postgresql status 
```

test