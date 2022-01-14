# MonstAR
MonstAR is the combination of Monsters and Augmented Reality. It augments the physical experience of playing card games like Pokemon or YuGiOh. 
It´s a project which will be developed by Andreas Riedel, Michael Kronester and Daniel Peters in frame of the AR VR course in UXDM WS21.
## Idea
The goal of the app is to train monsters and have them fight each other. Each monster has a unique game card that can be tracked through image recognition. When the game card is tracked, the monster is displayed in a 3D model on the game card. It is also possible to uplaod the image of the game card on a smartwatch in order to acess AR functionality and inspect/check on the monsters on the go. Once two cards are placed so that they face each other, the monsters can fight each other through actions on the screen. Each monster has several development possibilities. They can be trained/pushed by connecting them to a fitness app. Through your walking, standing and fitness actions, the monsters can be then leveled up and potentially evolve. Furthermore, all collected monsters can be viewed in detail in a separate portal. When you enter this portal, you will see a list of all the monsters you have in real "human" size.

##Wiki

[MonstAR Wiki](001_MonstAR_Documentation_Kronester_Peters_Riedel.pdf)

## Technical 
### General:
* Mobile Device with possibility to use AR Technology 
* (Smartwatch)
* Playcards with image of the Monsters to track 
* Space to walk around for the Portal View

### Technical needed for Implementation: 
* Unity, VSCode, xCode, AR Foundation Plugin
* Apple ARKit
* Device with MacOS for running and building the app on xCode 

### Interaction Techniques: 
* The user can project a 3D model of the monsters on the cards by focusing the respective cards with the camera.
* The user has the possibility to view the monsters stats through an augmented UI next to the monsters 3D model.
* The user can have the monsters fight or interact with each other through touch interactions on the screen.
* The monsters can be viewed in real "human" size and in every detail by walking through the portal, walking around the monsters and pointing the AR on them




## Components
Mobile Scene
Image based tracking (on Card but also possible on Smartwatch).
Augmentation of 3D Models of Monsters on the image.
Augmenting Monster Stats around the monster.
Battle Mode between two monsters as soon as two images are recognized and monsters look at each other

Monster Reserve
Walking through a portal into a monster reserve.
seeing all collected monsters in their true size.

## Design Examples
The Design is meant to be abstract and playful. The Habitat will look friendly as it is the natural habitat of your monsters.

### Monsters 
#### Variations

![alt text](https://assetstorev1-prd-cdn.unity3d.com/package-screenshot/19555c19-4707-4397-b524-4ced3d50d83b.webp "Asset Example for Monsters Variation")

#### Evolutions
![alt text](https://assetstorev1-prd-cdn.unity3d.com/package-screenshot/6af24812-3c8c-4e76-88ff-cf1784858b79.webp "Asset Example for Monsters Evolution")

### Habitat Modules Examples
![alt text](https://assetstorev1-prd-cdn.unity3d.com/package-screenshot/b46b9a10-e3b1-455b-af2d-9d13f892053e.webp "Asset Example for Enviromental Modules")
![alt text](https://assetstorev1-prd-cdn.unity3d.com/package-screenshot/7602c1f9-0654-4d4d-ad0f-8973c6730388.webp "Asset Example for Enviromental Modules")
![alt text](https://assetstorev1-prd-cdn.unity3d.com/package-screenshot/3c0cc048-a7c3-4cf5-8c08-ad008c13c11e.webp "Asset Example for Enviromental Modules")



## Implementation Plan

| Time     | Deliverable          | Notes |
| ------------- |:-------------:| -----:|
| 01.11. - 05.11.     | Personas, User Stories, Requirements  |  |
| 06.11. - 26.11.     | Prototype: Image tracking with minimal functions Portal with minimal Content inside    |    |
| 01.11. - 05.11. |   Proof of work  |     |
|27.11. - 10.12. |Usability Test on 30.11. & 01.12. ||
|until 10.12.|Iteration for improving Prototype||
|10.12.-23.12.|Final Development||
|24.12.|Code freeze! Working on Documentation||
|16.01.|Documentation Hand-In||
 

 



