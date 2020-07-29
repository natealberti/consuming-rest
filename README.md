# consuming-rest
Consumes data from a Restful web service

This application uses Spring's RestTemplate to retrieve the data from the web service. The Quote class is set up to take in data, and it passes through the Value class, then the ConsumingRestApplication.java where it uses CommandLineRunner to push the data it recieved from the web service to the command line. 
