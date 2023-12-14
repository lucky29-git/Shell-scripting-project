# Shell-scripting-project

As a devops engineer we have to maintain a lot of repos 
This shell scripting projects helps in maintaining the list of all the users who access to your organization repo's

Using github api we can 

run following command -

export username="<your_github_username>"
export token="<your_github_PAT>"

./bash-script.sh <your-organization-name> <repo-name>

for example , ./bash-script.sh kubernetes community

if it shows  (run the following command)
 
1.permission denied error 

chmod 777 bash-script.sh
./bash-script.sh <your-organization-name> <repo-name>

2. jq command not found

sudo apt install jq -y
./bash-script.sh <your-organization-name> <repo-name>
