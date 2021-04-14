---
title: "UnSting"
date: 2018-06-20T11:22:38+05:30
---
An end-to-end disaster recovery and management platform using decentralized swarm robotics (autonomous drones) using RTC (Realtime Communication) powered by agora.io to detect and track people in need of help. This information is relayed by our platform to people who are willing to help. The platform seamlessly integrates volunteers, people in need of help, and other interested parties.

Drones collect information through a live stream that is sent to the servers in real time. Using the orientation of the drone and some assumed properties, the geo-location of the affected person is detected by mapping his location in the 2D image to a 3D coordinate using a custom-built algorithm. This data is plotted on a dashboard and sent to a PWA (Progressive Web App) to assist on field search and rescue operations.

### Drones
The drone carries a high definition camera and equipment to relay the video feed to the base station in real time. This feed is the processes along with some additional information from the drone.

{{< figure src="/drone.gif" title="Drone" caption="Drone: Hexacopter V1" position="center" >}}

The drones follow a hexagonal mapped path. This allows the drones to cover the maximum affected area in the miminum amount of time. The hexagonal grid pattern over the area shows the path followed by the drones.

{{< figure src="/drone_path.gif" title="Path" caption="Haxagonal path mapping followed by the drones" position="center" >}}

### Object detection
The application makes use of object detection on the video feed to find people in need of help in the affected areas. This data is then combined with addition geo data and an algorithm converts this 2D image to a 3D geo location coordinate.

{{< figure src="/detect.gif" title="Detect" caption="Detecting multiple people from the live video stream" position="center" >}}

### Application
The entire concept is tied together by the application that allows the users to monitor the situation and guide the serach and rescue teams on the ground.

###### Dashboard
The dashboard is a overview of all the moving parts of the disaster management and recovery platform. It allows for a team to view all the aspects of the situation and make decisions related to resources and on ground rescue teams.

{{< figure src="/dashboard.gif" title="Dashboard" caption="Dashboard view of the entire search and rescue operation" position="center" >}}

###### App
The Progressive Web App (PWA) allows users to sign up as volunteers and aid in the operations. They can view the location of other volunteers and people in need of help and also communicate through the chat interface.

#### Team
[@nishnash54](https://github.com/nishnash54) [@Souldiv](https://github.com/Souldiv) [@SuryaThiru](https://github.com/SuryaThiru) [@samyak-jain](https://github.com/samyak-jain) [@technophilic](https://github.com/technophilic)
