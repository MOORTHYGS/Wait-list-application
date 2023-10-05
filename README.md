# Wait-list-application
# Waiting_list_
This app allows a potential customer to sign up to the waiting list 
with his email address.
Intilly the user can view the login page 

![image](https://github.com/MOORTHYGS/Wait-list-application/assets/82669708/b25aca28-d624-42fb-aec6-4eee49644aab)



if the user is new then he will be redirected to create account
with the requuired fild
#Name
#Email
#password
#conform Password



 while registration the user  need to vrify the otp , 
 An OTP is sented to the user Email address

 ![image](https://github.com/MOORTHYGS/Wait-list-application/assets/82669708/25ded9ac-a318-4c57-95ad-469056036f70)

  after login the user can see their referal link 
  He can share this link to his friends.
  As soon as he signs up, his position in the waiting list will be 
displayed.As soon as he signs up, his position in the waiting list will be 
displayed.




- If their friends sign up using his referral link, he will “move up 1” by 1 
place in his position
For that initially the user position is 99 which is stored
if the referal link is used for 1 time
then,
the position is redused by 1
(decreament operation)


if(referel_ins)
positions=get.user_position[]
for(int i =0;positions<i;i++)
user_position=user_position[]-1;



oncce  the user reachs position 1
he will get an coupon code to purchase the new product.






