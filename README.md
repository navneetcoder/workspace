# gx_space

## Using Azure

```
python -m pip install 'great_expectations[azure]'
```

### host and share data docs

```
pip install azure-storage-blob
```

```
pip install snowflake-sqlalchemy
```

gxstore
sudo apt install postgresql

pg_ctlcluster 12 main start

sudo visudo
$ whoami
<USERNAME>      ALL = (ALL) NOPASSWD: ALL

sudo -u postgres psql
create user gxuser with password 'gxuser'
ALTER USER gxuser WITH SUPERUSER
create database gxdb
\l
\d

tcp/ip
/etc/postgresql/*/main/pg_ident.conf
listen_addresses = '*'

sudo vi pg_hba.conf
host    all             all             127.0.0.1/32            md5


sudo service postgresql restart;



add 
