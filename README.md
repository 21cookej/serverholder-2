# EaglerCraftX Server Setup
## Introduction
Eaglercraft is an open-source web-based minecraft copy. Today I will teach you how to setup a public server with plugins for free! Please note that the project is an old one, and is not being actively maintained anymore. Because of this, you should consider hosting the server on a system outside of your network. Some examples include OCI and Github Codespaces. Now, lets begin! 

## Installing The Server
Now, open 2 terminal tabs in the new server directory and paste in the following snipits:
<br>
<br>
first tab: `cd server && sudo java -jar server.jar`
<br>
<br>
second tab: `cd bungee && sudo java -jar bungee.jar`
<br>
<br>
## Making Server Public
Great! Now, you need to forward ports  `8081` and `25565` and navigate to your servers public ip [server-ip:8081]. The server welcome page should be displayed. Congrats on running your own server!

## Installing Plugins
In order to install plugins, navigate to `server > plugins`. You will need to clone the initial [plugin-name.jar] file as well as creating a separate directory in the plugins folder in order to store the additional data. Then just restart the server and the plugin should be running!