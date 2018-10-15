### Credits

This repo was forked from https://github.com/bshetti/api_server. Bill Shetti is the original creator of Api_Server. Modification have been made to the codebase and installation with input from Jacob Cherkas and myself.

## Contributors
Bill Shetti
Jacob Cherkas
Sean O'Dell

# OS Requirements (Tested on Ubuntu 18.04)

sudo apt-get update & sudo apt-get upgrade -y

sudo apt-get install python python-pip libmysqlclient-dev -y

pip install sqlalchemy flask statsd requests mysqlclient

# Install fitcycle

git clone https://github.com/theseanodell/vcs-apiserver.git ~/apiserver

# Run Apiserver

cd apiserver/

modify/update ID, Password and Server in mysql.env

    MYSQL_ID='db_user'

    MYSQL_PASSWORD='abc123'

    MYSQL_SERVER='10.10.10.10'

to run ./startapi.sh