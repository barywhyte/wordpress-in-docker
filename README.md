 # Creation of a dockerized wordpress app running on google compute engine
 
 ## A little background to Microservices with docker
 
 #### prerequisites

* Google Cloud Project
* Enable billing for the project
* Enable relevant APIs (e.g compute engine API)

## Steps
* Launch a f1 micro VM (Trust me, its more powerful than you think!)
* Create a directory in the VM server. cd and initialize git repo
* Create docker-compose yaml file for wordpress, mysql/postgresql, nginx and optionally SSL cert. services
* Bring up the entire stack in one liner with : docker-compose up -d
* Navigate to your IP on broswer and complete wordpress installation
* Setup your domain name with Google Cloud DNS to route traffic to a specific domain and chanhe IP address to static 

####END
