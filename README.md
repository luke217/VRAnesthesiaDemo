##Instruction on this Version:

Before using the zip file of VR anesthesia, please run the OculusSetup.exe to configure the Oculus environment on your computer and this is a prerequisite to run the Application of VR anesthesia.

When running OculusSetup.exe, better configure it by default directory on ‘C:\Program File\ Oculus’, otherwise the VR application may not run normally.

After configuring the Oculus Environment and downloading the Ver1102.zip, you can directly distract the zip file and run the VROperationRoom.exe and there you go, enjoy and have fun!


##Game Flow Demonstration:
https://youtu.be/_Rz22sSVqt0
or
https://www.bilibili.com/video/av35252377/


##Update Note
Version Update: Ver1102.zip 
Update Time: Nov 2nd 2018

###Update Content:
	So this is the first integrated version including VR and PC. Except for the anesthesia monitor development, all the other work have been settled down like interaction and network.
All in all, it is like a demo or a conclusion for the current stage. But I will still list some parts which needs to be improved in the future.

###ToDoList:
On the student side:
PC:
“Injection” and “takeSyringe” animation IK still not natural.
Debug warnings and use profiler to increase performance
Student view instruction design
	VR:
Get a better remote avatar like with either complete body of a surgeon or an incomplete surgeon model edited in Maya
Spatial Sound of heartbeat and the sound of environment.
	General:
Nurse’s AI design enables the interaction between a nurse and the player including sound and gesture and their IK system.
Get more smart object in the scene.


On the instructor side:
Add more parameters in Waveform control panel(Specified by George)
Improvement on SPO2 and CO2 waveform

Alert: Sometimes, the application may not connect to the server or cannot find room in the lobby and it’s likely about the photon server’s service update. We could get two version of the app with one set to region of US in photon cloud and the other set to ‘Best Region’ which will be chosen by the server automatically. It’s not a guarantee that which one of them would run normally, but it worth a shot to try both. If neither of them work, I will debug it and find out why and give it a fix. In the future, I may consider building a server specifically for this app according to the goal of the next stage development and the given financial support.

