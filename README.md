# OpenSourceTraining

## Purpose

So the purpose of this guide is to share training documentation and examples to the security community.



## Implementation

I have tried to structure the training in a slightly different method so that common documentation can be reused with different views of the content. 

As an example, DNS for each DNS topic I would like to present common documentation but then have contextual information of how that topic will apply to a role.


### Blue Hat Security
- DNS is one way that an attacker will profile your infrastrcture and you should be aware of the information that is visible online. e.g charles-test.domain.com could give away that you have a user called charles and if ssh is open that might be a user to try when bruteforcing. Furthermore jira.domain.com can let an attacker know you are running the jira service. Based on this they can tailor phishing emails and find relevant CVEs for the platform


### Attacker Perspective
-  For an attacker dns host names can give a lot of information on a target infrastrcure from software used to versions and potential usernames. Common tools for enumeration are X,Y,Z. 


### Common Info

DNS is a name to ip address technology and is composed of several category of record. 


e.g 

google.com    A       1.2.3.4


So the above fake record the hostname google.com maps to an ip address 1.2.3.4 So when you type www.google.com into your browser it will resolve the ip using your dns provider and then send a http get request to that ip on the port 80. One ip can have many host entries.


# TODO Flesh out the examples and work out a good method for contributing documentaton

