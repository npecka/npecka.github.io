---
layout: article
titles:
  # @start locale config
  en      : &EN       Projects
  en-GB   : *EN
  en-US   : *EN
  en-CA   : *EN
  en-AU   : *EN
  zh-Hans : *ZH_HANS
  zh      : *ZH_HANS
  zh-CN   : *ZH_HANS
  zh-SG   : *ZH_HANS
  zh-Hant : *ZH_HANT
  zh-TW   : *ZH_HANT
  zh-HK   : *ZH_HANT
  ko      : *KO
  ko-KR   : *KO
  fr      : *FR
  fr-BE   : *FR
  fr-CA   : *FR
  fr-CH   : *FR
  fr-FR   : *FR
  fr-LU   : *FR
  # @end locale config
key: page-projects
---
Home Kubernetes Lab – Kubernetes Deployment using Rancher Flavor
  Previously used, Endpoint was configured to be a bare metal VMware ESXI host. A 3-node cluster was built upon the ESXI host using RKE to deploy Kubernetes atop the hosts.  Another individual host was designated as the entry point serving an NGINX load balancer  across the three nodes. To make this work the master node Exchanged SSH keys with the  three nodes for a successful RKE deployment. Once up, kubectl, and helm were installed  for Kubernetes CLI integration and chart deployment. Rancher was deployed via a HELM  chart and given proper configuration values. The Rancher cluster was also secured via the  local admin account and with a certificate that was generated from the home domain root  CA that also had to be generated and created. This cluster then has been used to test  various Kubernetes versions of apps serving things including DokuWiki, LDAP load  balancer, storage provisioning, etc.  

Home Network – Network Configured with PfSense & Pi-Hole 
  Implemented security infrastructure on the home network. Flashed a machine to serve as a PfSense firewall and work as a DHCP server. This required removing the google fiber  router from the equation and instead routing the fiber connection straight to the firewall  and configuring the WAN/LAN properly to accept that type of connection. Each LAN was  isolated from one another as to separate a home network to a guest network and restrict  devices from accessing the internal from the guest. A Raspberry Pi was introduced to the  network and had Pi-Hole deployed on it. Pi-Hole served as a DNS server for the network  and as an ad blocker for all machines on the network. The firewall was pointed to the  PiHole for DNS and all items on the network sourced through the new DNS. Through all of this a home domain was able to be established for all machines, labs, and services on  the network.  

RTOS Uniprocessor GUI Scheduler 
  Using Python programming, developed a GUI implementation of a task scheduler for Rate Monotonic (RMS) and Earliest Deadline First (EDF) schedulers. The program allowed an end user to load a GUI and then input by either manual entry, or by mass entry via an excel document a list of task sets. They would then be given output either via the GUI screen or to a new excel document of the task set(s) output being scheduled using RMS, EDF, or both.  

Chatbot – Written in Go & React 
  Developed a chatbot using the Go and React.js language. This was a learning exercise to  get an introduction to both Go and React. The app was deployed using a Platform as a  service (PAAS) method Heroku that served the app for free on a use only basis. For the  Client-side, the app uses HTML, CSS, JavaScript, and react to make a front-end of the app.  Then Go was used to write the Server-side of the app.  

Recipe App – Recipe Finding App Written in Java 
  An app written using Java and Android Studio. The goal of the app was to provide the user a GUI interface to document the food they have around the house and then generate an output of recipes based on the entered ingredients. The app runs on Android devices and uses a MySQL database to catalog the entered items and then back-end logic sorts through the list comparing it to a known list of recipes to output to the user. The app communicates with the database using the Volley library.  

Game Engine – Game Engine Written using OpenGL 
  This program was written as a learning initiative to venture into game programming. Using online resources, the team was able to construct a game engine using the OpenGL library with the Java coding infrastructure. Using various vertex algorithms, the team created a game engine that outputted a character that could move around and explore a randomly generated terrain. 