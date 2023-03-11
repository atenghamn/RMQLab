# RabbitMQ Lab


## Run docker image 
 docker run -it --rm --name rabbitmq -p 5672:5672 -p 15672:15672 rabbitmq:3.11-management

## Log in 
@ http://localhost:15672/
username/password : guest

## Start Node apps
node sub.js "#" to listen to "everything" 

## Start CSharp app
dotnet run "#"
