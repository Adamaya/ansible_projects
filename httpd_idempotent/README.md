# Approach
To make httpd restart service idempotent there is a way in which we execute the curl command using ansible command module and check the webserver is working or not in the system if it is not working then the exit code will be non zero after performing that certain task store the output of that task in a variable. A condition for restarting httpd service task can be created that if return code != 0 for the curl task then only run the command of restarting the httpd service should execute else it would not run the restart command.
# Detailed Blog
[blog link](https://medium.com/@adamaya.sharma_iot18/how-to-make-httpd-restart-service-idempotent-in-ansible-5b8079576fd1)
