# api_server

Load into whatever directory.


Modify mysql.json file with the right password and server and username for the DB


Modify the line "with open('../mysql.json') as json_data:" to "with open('mysql.json') as json_data:"


Modify the last line "app.run(host='172.31.9.213', port=5000)" with the right IP address


to run  ./api_server.py 


# image build

git clone directory

If you want to run ALPINE LINUX:
cp DockerfileAlpine Dockerfile
docker build -t miniapi .

If you want to run ubuntu LINUX:
docker build -t workingapp .


# run image

docker run -p 5000:5000 {miniapi or workingapp}

