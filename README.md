# Node-RED_OBS-WS_5.X
Node-RED flow to control OBS using OBS Websocket 5.X

## Prerequisites 
- [Node-RED](https://nodered.org/)
- [OBS Studio](https://obsproject.com/) > 28.x (OBS WS 5.x is included by default)
  - If you are using OBS < 28.x you need to install [OBS WS 5.X](https://github.com/obsproject/obs-websocket/releases/tag/5.0.1) manually 

## Dependencies
- BasicFlow.json : no dependencies
- DashboardDemo.json : [node-red-dashboard](https://flows.nodered.org/node/node-red-dashboard)

## Setup (Basic flow with no GUI)
- Import the [flow](https://github.com/n3odym3/Node-RED_OBS-WS_5.X/blob/main/flows/BasicFlow.json)
- Change the IP (URL) of the streaming PC on the WS config

<img src="https://github.com/n3odym3/Node-RED_OBS-WS_5.X/blob/main/img/ws_server.PNG" width="70%">

- Change the password (msg.payload) and clic on the "Inject" node to save it 

<img src="https://github.com/n3odym3/Node-RED_OBS-WS_5.X/blob/main/img/password.PNG" width="70%">

- Start OBS
- Wait for the OBS WS connection (it can take a few tens of seconds)
- Edit the examples 
  - Scene name
  - Text : source name and value
  - Audio : source name
  
<img src="https://github.com/n3odym3/Node-RED_OBS-WS_5.X/blob/main/img/examples.PNG" width="70%">

- DONE !

## Setup (Demo GUI)
- Import the [flow](https://github.com/n3odym3/Node-RED_OBS-WS_5.X/blob/main/flows/DashboardDemo.json)
- Set the password and clic on the button 

<img src="https://github.com/n3odym3/Node-RED_OBS-WS_5.X/blob/main/img/passwordgui.PNG" width="35%">

- Try the dashboard 
  - Switch scene
  - Edit text source
  - Select autio source
  - Toggle Mute
  - Set the volume

<img src="https://github.com/n3odym3/Node-RED_OBS-WS_5.X/blob/main/img/dashboard.PNG" width="50%">
 
 - DONE ! 

Go to the [OBS WS 5.0 documentation](https://github.com/obsproject/obs-websocket/blob/master/docs/generated/protocol.md#events-table-of-contents) for more infos 





- My [Twitch channel](https://www.twitch.tv/ioodyme)
- To [support me](https://paypal.me/ioodyme)
