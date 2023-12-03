# test_login
test task with login and authorization, postgresql is used as a database, the project is packaged in docker

## HOW TO RUN PROJECT
make sure that your ports 8001 for the app and 5432 for postgres are free
- `cd test_login_auth`
- build project `docker-compose up -d --build`
- and app is available in http://0.0.0.0:8001/
- 
-  documentation with swagger in http://0.0.0.0:8001/api/docs/
-  signup
-  http://0.0.0.0:8001/api/signup/
-  signin
-  http://0.0.0.0:8001/api/signin/

