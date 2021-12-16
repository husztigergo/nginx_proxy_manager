#### Default admin user:

Email:    admin@example.com
Password: changeme

#### Make sure that the app you want to expose is connected to the NGINX proxy manager network “nginxproxymanager_default”.
docker run --network nginxproxymanager_default --name=postgres postgres
