"# HW3-vpc" <h1> 

**first step: creating a VPC**</h1>


![alt text](https://github.com/OsamaAboraya/HW-3/blob/main/WhatsApp%20Image%202021-05-02%20at%2015.45.40.jpeg)


<h2>2-creating two subnets :</h2> 
    
    1-wordpress
    2-sql-db
   
   
![alt text](https://github.com/OsamaAboraya/HW-3/blob/main/WhatsApp%20Image%202021-05-02%20at%2015.45.40%20(1).jpeg)
    

<h2>3-internet Gateway</h2>

![alt text](https://github.com/OsamaAboraya/HW-3/blob/main/WhatsApp%20Image%202021-05-02%20at%2015.45.41%20(1).jpeg)


<h2>4-Nat gateway </h2>


![alt text](https://github.com/OsamaAboraya/HW-3/blob/main/WhatsApp%20Image%202021-05-02%20at%2015.45.42.jpeg)


<h2>5-Route Tables</h2>

![alt text](https://github.com/OsamaAboraya/HW-3/blob/main/WhatsApp%20Image%202021-05-02%20at%2015.45.41.jpeg)

final step: create two instance, first one for clinet-side(wordpress) , second one for dp(server)

![alt text](https://github.com/OsamaAboraya/HW-3/blob/main/WhatsApp%20Image%202021-05-02%20at%2015.45.42%20(1).jpeg)


<h3>*the tow instance conaines a docker-compose.yml file*</h3>

<h2>How to Run:</h2>  we run the docker-compose on both instances by $ docker-compose up 

after that we browse to :(wordpress public ip):8080


**if every thing is working will --->
![alt text](https://github.com/OsamaAboraya/HW-3/blob/main/WhatsApp%20Image%202021-05-02%20at%2015.45.38.jpeg)

