# kubectlCommands

1. ListPodsAndItsAZ
    This is a function which can be added in the bash profile. To get the pods and the AZ to which it is scheduled just run the below command.
    
    listpods "mynamespace" "-l app=myapp"   | sort 
