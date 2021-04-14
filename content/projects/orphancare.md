---
title: "OrphanCare"
date: 2017-11-04T01:05:12+05:30
---
A platform to empower the public, provide help to children and orphans and protect them from abuse.

We provide a platform that keeps the sensitive data secured by blockchain, uses FaceNet deep learning algorithm for facial feature recognition and cloud computing for big data analysis. We also integrate GPS location and implmented a form of YOLO to trach and find the children.

A simple and easy to use PWA just allows the user to take a picture of a child. Face recognition and tracking is done with this data. To optimize the solution all the computation is distributed to the cloud.

### Problem statement
India, with its growing population, is experiencing a growing no. of children who are left unattended in the streets for various reasons. There is extreme difficulty is mapping those in need and to rescue them from the streets. We wanted to solve this problem by using blockchain and face recognition empower the public with a platform to fight child mistreatments and child abuse.

### Objectives
 - Using blockchain and face recognition empower the public with a platform to fight child mistreatments and child abuse.
 - Provide a platform for NGOs that target rehabilitation of unattended street children/orphans
 - Empower any user to help eradicate a gloomy future for these kids
 - Make it cross-platform so as to ensure maximum usage and no restrictions

### Architecture
The proposed design is an Progressive Web App that runs on all platforms irrespective of Operating Systems. The application allows the user to take a geotagged image which delivered to a web server which again forwards it to a search and match server which functions as a matcher. The search and match servers run facial recognition algorithms and checks from the database for image data matching to anything in the database. If a match is found, the concerned organisation can view the geotagged image and the location of the child found. The organisation can take further action accordingly.

{{< figure src="/orphan.png" title="Application" caption="OrphanCare: Application architecture" position="center" >}}

#### Team
[@apuayush](https://github.com/apuayush) [@nishnash54](https://github.com/nishnash54) [@SuryaThiru](https://github.com/SuryaThiru) [@samyak-jain](https://github.com/samyak-jain) [@technophilic](https://github.com/technophilic)
