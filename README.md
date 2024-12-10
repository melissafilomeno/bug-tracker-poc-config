# bug-tracker-poc-config


Pre-requisites:
* Postman 11.19.0


Configuration Setup (encrypted values) :
* Start config server (bug-tracker-poc-config-server)
* Go to config server repo, import environment and management postman collection /postman
* In the body tab, set config to be encrypted
* Update config file with encrypted value in below format :
  "{cipher}<encrypted value>"
