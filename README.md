# OS Requirements (Tested on Ubuntu 18.04)

sudo apt-get update & sudo apt-get upgrade -y

sudo apt-get install python python-pip libmysqlclient-dev -y

pip install sqlalchemy flask statsd requests mysqlclient

# Install fitcycle

git clone https://github.com/theseanodell/vcs-apiserver.git ~/apiserver

# Run Apiserver

modify/update ID, Password and Server in mysql.env

MYSQL_ID='db_user'

MYSQL_PASSWORD='abc123'

MYSQL_SERVER='10.10.10.10'


to run  ./apiserver.py