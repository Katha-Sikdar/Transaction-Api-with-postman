# Transaction-Api-with-postman

## Prerequisite
- NodeJS
- PostMan

## About This Project

This is a demo Transaction API which can create Admin, Customer, Agent, Merchant account. Besides this, the transaction API's also able to update users informations such as 
- ID, Name, Role, Phone Number, NID number and so on and can check balance of all of the users account.
Among them, Few API's have transaction logics such as,
1. System can not deposit money to the Merchants and Customer account.
2. Customer can not withdraw money from Merchant and other Customers, can withdraw money only from Agent Account.
3. No system charge will be applicable for depositing money from syatem to agent. But System get commisions 25 tk per thousand.
4. Agent can deposit money to the customer account in that case commision will be 25 tk per thousand and this commission will be added into agents account.
5. Customer can withdraw money from agent and in that circumstance agent will get 25 tk commiosion per thousand. and money transaction fees for customer is 5Tk and customers withdrawal dees is 10 Tk per thousand. and so on.


## How to run this project
-Clone this project
``` https://github.com/Katha-Sikdar/Transaction-Api-with-postman```
- In the source root project, give following command:
  ``` npm i ```
- Give following command to run :
   ```npm start ```

## Few attachments after executing the project

![1](https://github.com/Katha-Sikdar/Transaction-Api-with-postman/assets/82141562/d5536c85-bdbb-48b3-ab33-00945353d0ec)
![3](https://github.com/Katha-Sikdar/Transaction-Api-with-postman/assets/82141562/4ee8b1ad-721c-4262-8f87-13982482fb41)

<h1> Test case, Bug Report, and Bug Advocacy Link</h1>
<a href="https://drive.google.com/drive/folders/1XzLWkP4FRpqiQ73ETHZUDT79VKU7AqLP?usp=drive_link"> Click Here to visit the link!</a>


