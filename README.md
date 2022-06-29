	I follow the original project
https://nginxproxymanager.com/setup/

	How it work

	I clone the project
git clone https://github.com/PabloCarrai/nginx-proxy-manager-example.git
	Access to the project folder
cd nginx-proxy-manager-example/
	I generate a .env
cat .env-example >> .env
	I raise the same
docker-compose up -d

```
http://127.0.0.1:81
Default Admin User:
Email:    admin@example.com
Password: changeme   
```
