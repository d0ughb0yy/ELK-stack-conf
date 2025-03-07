# ELK-stack-conf

## About the project
This repository is related to my ELK stack project where I setup an Ubuntu server running the ELK stack (Elasticsearch, Logstash and Kibana) and an Ubuntu client server running an FTP server, SSH server and HTTP server. The client server sends logs using beats, Filebeat for logs and Packetbeat for network traffic.

## Objectives Achieved
* Setup both the ELK server and Client server
* Setup the SSH and FTP servers on the client and enabled logging
* Visualized failed SSH and FTP login attempts using Kibana dashboard
* Able to visualize incoming and outgoing network traffic from Packetbeat in Kibana

## Things to do
* Setup alerts for failed SSH login attempts going over the assigned threshold, same goes for FTP logins, suspicious file transfer on the FTP server
* Setup the HTTP server running a simple static site
* Filter the data concerning that site using Logstash and visualize it in Kibana
* Start setting up malware alerts for when the client gets compromised 