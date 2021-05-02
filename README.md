"# HW3-vpc" <h1> 

**first step: creating a VPC**</h1>


![alt text](https://github.com/OsamaAboraya/HW-3/blob/main/WhatsApp%20Image%202021-05-02%20at%2015.45.40.jpeg)

<h2>
2-creating two subnets : 
    1-wordpress
    2-sql-db
 </h2>   
![alt text]( https://github.com/OsamaAboraya/HW-3/blob/main/WhatsApp%20Image%202021-05-02%20at%2015.45.40%20(1).jpeg)
    

3-internet Gateway
![alt text](https://github.com/OsamaAboraya/HW-3/blob/main/WhatsApp%20Image%202021-05-02%20at%2015.45.41%20(1).jpeg)


4-Nat gateway 
![alt text](https://github.com/OsamaAboraya/HW-3/blob/main/WhatsApp%20Image%202021-05-02%20at%2015.45.42.jpeg)


5-Route Tables
![alt text](https://github.com/OsamaAboraya/HW-3/blob/main/WhatsApp%20Image%202021-05-02%20at%2015.45.41.jpeg)

final step: create two instance, first one for clinet-side(wordpress) , second one for dp(server)
![alt text](https://github.com/OsamaAboraya/HW-3/blob/main/WhatsApp%20Image%202021-05-02%20at%2015.45.42%20(1).jpeg)

*the tow instance conaines a docker-compose.yml file"

How to Run: we run the docker-compose on both instances by $ docker-compose up 

after that we browse to :(wordpress public ip):8080



if every thing is working will --->
![alt text](https://github.com/OsamaAboraya/HW-3/blob/main/WhatsApp%20Image%202021-05-02%20at%2015.45.38.jpeg)

