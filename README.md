# Web_panel
panel for election
_SERVICE web:
go to detection web 
run:
docker-compose up // up service to port 8080
for test open url in browesr localhost with port or docker container ip
localhost:8080

it show vote page
you must login to see candidate
in login page enter email and password to create and login
(if email not found it create first)
then back to home and vote your candidate by click

*************
if you are admin you can go to url  below
localhost:8080/admin

default id : 1234
		password : 1234
		
then go to dashboard and change it !

in dashboard you can see how many vote 
				 can create candidate
		
		
you can access api from webapache

this api call others api (like view server or dispacher)
for call other apis use api address below
webapache/cloud/public/api/web

get param : url //user of api
post param : all params that api need


finish
