**Spring-boot-rest-master**

This is a Spring Boot API project that allows you to enroll Students in a classes.

The project uses Spring Boot, Spring Data JPA, and MySQL database.

To run the project, clone or download it, and then run mvn Spring-boot-rest-master:run or just import the program into your IDE.

Clone the project
git clone https://github.com/codeselenium/Spring-boot-rest-master.git
mvn clean Spring-boot-rest-master:run


**Use postman for below queries.**

Students list

url: https:{domain}/api/v1/students
method: get



Students By id

url: https:{domain}/api/v1/students/id
method: get

Students create

url: {domain}/api/v1/students
method: Post
data: { "firstName": "test", "lastName": "test", "aclass": { "name": "3 A" }, "nationality": US"}


Students update by id

url: https:{domain}/api/v1/students/id
method: Put
data: { "firstName": "testOne"}
