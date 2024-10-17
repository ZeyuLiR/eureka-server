# eureka-server
  
For packing spring boot project to docker repo: 
	command: mvn compile jib:dockerBuild
 
reference: https://github.com/GoogleContainerTools/jib/tree/master/jib-maven-plugin



After loading all images in your docker, run a container of mysql. The container's username is root and the password is root123456 and the port is 3306

Then, run microService.sql in your database.


In the end, you can run docker-compose
	command: docker compose up
 
reference: https://docs.docker.com/reference/cli/docker/compose/up/


For stripe
Download stripe cli first and then use stripe sk_key to login
When you login stripe account, it may use my email and password, please tell me.
After login, you need to start stripe webhook listening

Reference: https://docs.stripe.com/webhooks



The github links of source code:


https://github.com/ZeyuLiR/eureka-server


https://github.com/ZeyuLiR/userService


https://github.com/ZeyuLiR/tableService


https://github.com/ZeyuLiR/tourService


https://github.com/ZeyuLiR/gatewayService


https://github.com/ZeyuLiR/menu-order


https://github.com/ZeyuLiR/frontend

