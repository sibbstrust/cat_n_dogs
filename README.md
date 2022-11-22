# Voting application and infrastructure deployment

The deploy has two parts:

 * Infrastructure
 * Application


## Deploy

### prerequisites

 * A machine with ansible installed.

### application deployment


 ```bash
ansible-playbook playbook
 ```

###  Accessing the application

#### Voting

 ```bash
<server-ip>:31000
 ```

#### Result

 ```bash
<server-ip>:31001
 ```

#### Automated tests

The automated tests are done during :

 * Merging pull requests
 * Commits

For demostration purposes the tests are done on python files and there is only one python file from one of the containers which can modified.
