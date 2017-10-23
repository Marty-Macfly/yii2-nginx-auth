# yii2-nginx-auth

# yii/

Basic yii app with module yii2-nginx-auth installed


# nginx/

Nginx server installed and configured with ngx_http_auth_request_module

* https://developers.shopware.com/blog/2015/03/02/sso-with-nginx-authrequest-module/
* http://nginx.org/en/docs/http/ngx_http_auth_request_module.html

# src/

Source of yii2-nginx-auth module


You can run a test env with :

```bash
git clone https://github.com/Marty-Macfly/yii2-nginx-auth.git
cd yii2-nginx-auth/yii/
composer update
cd ..
docker-compose build
docker-compose up
```


- Nginx will listen on http://127.0.0.1:8888
- Yii will listen on http://127.0.0.1:8080
