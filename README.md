# nagiostraininglab
Nagios Lab Deployment with Docker

Requirements:

  Ensure you have docker installed.
  Ensure port 8080 is available or change it when deploying.

Run:
  Open CMD Window and run the following:
  
  docker pull jasonrivers/nagios
  docker run --name nagios4 -p 0.0.0.0:8080:80 jasonrivers/nagios:latest
  
Config:

  Edit config files under /opt/nagios/etc/objects/
  
Sample config file found in repository.
