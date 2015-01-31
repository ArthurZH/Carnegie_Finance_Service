# Carnegie_Finance_Service
This is development repositorty for Carnegie Financial Service, connecting AWS EC2 Deployment Instance.

Database: Amazon Web Service(AWS) RDS MySQL
Deployment: Amazon Web Service(AWS) EC2
Architecure: CMU-08600 Java-J2EEE HW9 MVC Architecture

File Structure:
-Packages
  -Controllers
    -Action
    -Controller
    -BuyFundAction
    -ChangeEmpPWDAction
    -ChangePWDAction
    -CreateCustomerAccountAction
    -CreateEmployeeAccountAction
    -CreateFundAction
    -CustomerAccountEditAction
    -
  -Model(DAO) CRUD Interfaces Completed: create() read() update() delete()
    -Customer
    -Employee
    -Fund
    -Transaction
    -Fund Price History
    -Position
  -Bean
    -Customer
    -Employee
    -Fund
    -Transaction
    -Fund Price History
    -Position
  -Form
    -RegisterForm
Database

if you want to access databases, please type follow command in your terminal.Then you will be able to remote AWS RDS MySQL and execute query

  mysql -h my-east-db-instance.cq6vzlml6j4g.us-east-1.rds.amazonaws.com -u root -p 12345678
  
Please note:
You are logged in as ROOT, be carefull about your operation in case affect others

How to configure to your local repository?

Two easy ways

1.Directly import from your Eclipse 
    --File
      --Imoort
        --Git
          --Project from Github
2.Clone the repository from your Github Client
      --Import Exisiting project
How do you know your configuration succeed?

Currenlty I implemented employee register action for testing.
After you run on your local Tomcat Server, You will see DAO Test page, once you click "Done" button, "Register Successfully" Message come out.

Congratulations! You totally did that correctly and start Coding your action and jsp now.

Let's Ace the Task!

Arthur Z.
Team 14 Infinity
Last updated: 1/30/2015
