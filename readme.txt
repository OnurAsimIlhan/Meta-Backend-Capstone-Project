for database and django admin panel superuser is:
name: admin
password: admin123

try using these
/restaurant #shows static welcome screen
get /restaurant/menu/ #shows the items on the menu
get /restaurant/menu/<id> #shows specific item on the menu
delete /restaurant/menu/<int:pk>	
put /restaurant/menu/<int:pk>	
post /restaurant/api-token-auth/ #get auth token