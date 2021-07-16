
##### TODO APP WITH DJANGO & REACT ###
#install django
#start project todo
#pipenv enronment
#description - > a simple todo app with django backend and react frontend

## Todo Model:
 # name, description, completed


 ##create super user
 ## create an API with djangorestframework & djanggo-cors-headers

 django-cors-headers is a Python library that will prevent the errors that you would normally get due to CORS rules. In the CORS_ORIGIN_WHITELIST code, you whitelisted localhost:3000 because you want the frontend (which will be served on that port) of the application to interact with the API.

## Create Serializers -to convert model instances to JSON so that the frontend can work with the received data.

## Create TODO Serializer

The viewsets base class provides the implementation for CRUD operations by default. This code specifies the serializer_class and the queryset