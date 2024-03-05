This is a small Project in cloud fomration which when executed will deploy all the resources required for a Mutli Tier Architecture!!!

The resource are written JSON template.


The Goal of this porject is to deploy a 3 tier Architecture web application infrastructure.

Public Tier - A web instance is lauched in the public subnet of the Network which allows HTTP and SSH traffic anywhere from the internet. When the instance is launched an Amazon Linux 1 O.S is installed on the system with Apache web server.

Private Tier - Similar like the public instance we have private instance which has internal access to Database. This instance however can not be accessed through the public internet instead can only be accessed with the network. It allows SSH traffic only from the public instance launched in the public subnet.

Database Tier - This a private subnet with a Database hosted inside this subnet and it allows SSH traffic from private Security group. The DB is MySQL.

View Completed-designer Png visualize the architecture.

I know I suck at documentation...So in case if you have any doubts reachout to me on LinkedIn.
www.linkedin.com/in/sonu-surendran-3b590b190

