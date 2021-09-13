Tier- Physical seperation of component not code.
Components- Db, backend server, ui, catching, messaging

![image](https://user-images.githubusercontent.com/46372483/132997988-c25ec42d-6564-4594-b6b1-c112ac8b14ea.png)

Single Tier system- All the services stays in 1 m/c
Adv:
data transfer withing m/c so easily and quickly. data Safer . less n/w latency as no n/w is req.
real performance depends on how powerful m/c is and software hardw/r req
Disadv:
less secure as every1 has auth to use every service.
once the code is pushed it cannot be stopped as once ui is pshed and the stop can't be done.
![image](https://user-images.githubusercontent.com/46372483/133000887-f26421d6-5606-4b25-8f7f-e79de65fe482.png)

2 Tier Architechture- client server arch. 
client is ui and business logic in 1 m/c. server has db hosted by business and has control.
![image](https://user-images.githubusercontent.com/46372483/133097993-6e653099-b3ac-4d6e-afcf-68fbe15a8739.png)

3 Tier Arch-  ui, business logic, db all lie in 3 diff ma/c and diff tier.
ui in 1 m/c, db in another and backend server in server like apache or node.
![image](https://user-images.githubusercontent.com/46372483/133099567-269d6145-0937-4501-9457-3eabaed51a06.png)

N-Tier Arch- is also caled distributed arch or system
eg- uber, fb, airbnb, pokemon Go.
catche, messaging queue for asynchronous behaviour, load balancer, search server for searching massive amount of data, components involved for processing massive am. of data, components running hetrogenous tech known as web services.

wht N-tier- 2 thing.
1. single responsibility princile
2. 

1. 1 machine has 1 task to do fully and resposibly, to give a full response.
    when a update or patch, only db would update without disturbing any1.
    if only db would be updating others would be up.
    code repo is diff for diff component 

layer vs tiers- 
layers are different codes. tiers are diff components.
