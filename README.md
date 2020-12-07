# cinema-microservice-brief-description

Theme: Cinema system 
Brief description: simple web application describes the cinema system using microservice architecture.  
Microservices: user service, auth service, cinema service, movie service, payment service. 
•	Auth service is responsible for authorization and authentication processes.  
o	Login o Authenticate 
•	Payment service-production of payment for cinema session clients. 
o	Charge 
•	User service-register user, get exist user, delete user, change/update user information o FindUser o GetAllUser o RegistUser o DeleteAccount o UpdateAccount 
•	Cinema service-movie showing, rooms seats management, news, timetable  o GetAllCinemaShowing 
•	Movie service- manage movie(add, delete, find) o GetAllMovie o GetMovieByID o GetAllGenre 
o	GetMovieByGenre 

The security of the application will be provided by the Zuul service.
Communication of services will be carried out using Kafka. Everything will be expressed in book-request services.
Authentication will be done through a JWT token using auth-service and common-service.  
