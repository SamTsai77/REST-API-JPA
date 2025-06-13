# REST-API-JPA
Demonstrate REST API and JPA features in JAVA + SprintBoot
 
Start: mvn spring-boot:run

![alt text](./pic5.png)

Add a customer: 
Post http://localhost:8080
{"firstName":"John", "lastName":"Smith"}

![alt text](./pic1.png)


List a customer:
Get http://localhost:8080/1

![alt text](./pic2.png)

Update a customer:
Put http://localhost:8080/1
{"firstName":"Jerry", "lastName":"Smith"}

![alt text](./pic3.png)


List all customers:
Get http://localhost:8080

![alt text](./pic4.png)