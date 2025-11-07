# list-users
This bash script gives the names of users who have read access to a particular github repository
This is done using github API integration.

Steps to use this script :
1. Clone this repository on your system/container and install jq.
2. Before executing list-users.sh, provide the below details :
    export username = "${YOUR_GITHUB_USERNAME}"
    export token = "${YOUR_TOKEN}"
3. Execute the below command :
    ./list-users.sh ORGANIZATION_NAME REPOSITORY_NAME
4. After executing the above command, you will get the list of users having read access to the repository mentioned.
