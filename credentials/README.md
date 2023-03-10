# Credentials Folder

## The purpose of this folder is to store all credentials needed to log into your server and databases. This is important for many reasons. But the two most important reasons is
    1. Grading , servers and databases will be logged into to check code and functionality of application. Not changes will be unless directed and coordinated with the team.
    2. Help. If a class TA or class CTO needs to help a team with an issue, this folder will help facilitate this giving the TA or CTO all needed info AND instructions for logging into your team's server. 


# Below is a list of items required. Missing items will causes points to be deducted from multiple milestone submissions.

1. Server URL or IP: 3.17.38.143 
2. SSH username: ubuntu
3. SSH password or key: .pem in folder called csc648-team1-fall-2021.pem
    <br> If a ssh key is used please upload the key to the credentials folder.
4. Database URL or IP and port used. 3.17.38.143:3306
    <br><strong> NOTE THIS DOES NOT MEAN YOUR DATABASE NEEDS A PUBLIC FACING PORT.</strong> But knowing the IP and port number will help with SSH tunneling into the database. The default port is more than sufficient for this class.
5. Database username: team1
6. Database password: CSC648Team1!!
7. Database name twohelpyouDB (basically the name that contains all your tables)
8. Instructions on how to use the above information.

No special instructions aside from following 
https://hackernoon.com/tutorial-creating-and-managing-a-node-js-server-on-aws-part-1-d67367ac5171
to access.

The mysql2 database is contained within the instance and can be accessed via port forwarding in mysql2 or directly in the instance using terminal.

# Most important things to Remember
## These values need to kept update to date throughout the semester. <br>
## <strong>Failure to do so will result it points be deducted from milestone submissions.</strong><br>
## You may store the most of the above in this README.md file. DO NOT Store the SSH key or any keys in this README.md file.
