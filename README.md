# OwlheadDemo
This program is a demo of the Owlhead Program created in Unity by the OwlHead team of the Tufts University IDEA Human Factors Lab. It is a VR game that gives the user a FOV far beyond the lense FOV of a normal headset. (Our current record for practical FOV expansion is expanding 96 degrees of vision to 155 degrees.) 

While the code of this project can't be shared due to security reasons, the general process can be. The purpose of this project is to test the usefulness of and expanded field of vision by creating spotting games the user can play at different FOV's. For this simulation, we created a game in which birds will fly at you, and the player has to scare them off by looking right at them and hitting a button. As part of the test, this game will be played at different FOV's to see how much benefit the expanded vision provides the player.
(Picture of the world simulation)
![IMG_1064](https://github.com/Cytadell/OwlheadDemo/assets/150078342/5520b9a7-797b-415e-baa0-58859a04e1cb)

While attempting to create a system that could expand a person's FOV in VR, we found that  all built-in softwares for UnityVR will not allow a programmer to change the field of view seen from the VR headset or any code regarding the image-mapping. This left us with a large design challenge as we were prevented from making any direct alterations to the headsets field of vision. After several failed solutions, we managed to bypass the issue by creating a simulated version of virtual reality using simulated curved screens and simulated cameras to create what is essentially, "virtual reality within virtual reality." By creating our own VR system on top of the UnityVR system, we were able to expand the players effective field of vision from 96 degrees (The normal FOV in VR) to 155 degrees.
(Normal 96 degree vison)
![95FOV](https://github.com/Cytadell/OwlheadDemo/assets/150078342/975fd44e-f7ea-4493-862a-7989c41019f6)
(Expanded 150 degree vision, note the image is more warped on screen then it is in VR)
![150FOV](https://github.com/Cytadell/OwlheadDemo/assets/150078342/4cb321ce-d0e0-4ab2-a290-059973f58d0c)

In this expanded vision the player has full range of motion and can easily spot things at the far end of their vision without moving their eyes and with little increased nauseousness. The expansion effect is natural enough such that upon returning to normal VR, most users thus far report feeling visually limited compared to their expanded vision. 

This project is currently about to begin offical testing and documentation this coming Spring 2024. A massive thanks to my lab mates Jo Chung and Owen Pendergast. We have been working on this project since day one almost a year ago!
(Picture of Jo, Owen and I in the lab)
![IMG_1056](https://github.com/Cytadell/OwlheadDemo/assets/150078342/593e9465-6e93-48d8-abcb-b18ccc279b4a)

