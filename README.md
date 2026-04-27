# AR/VR/MR Virtual Classroom

We created this project to turn our real-life AR/VR/MR classroom into a virtual one. It uses Unity to build the room and MetaHumans to represent the people inside, making the digital environment look and feel just like the real thing.

## The Room
While we aimed for accuracy, the room design is not a 1:1 replica of the classroom. We took some creative liberties based on the high-quality models we found online. 

<img width="975" height="556" alt="image" src="https://github.com/user-attachments/assets/4bb4abd3-ce17-488c-8f3b-3efce8ab7096" />


**Model Credits:**
* **Classroom Environment:** [Sketchfab Link](https://sketchfab.com/3d-models/classroom-46de5aba400a4f2aa8de907c0362d4a6)
* **Man:** [Sketchfab Link](https://sketchfab.com/3d-models/person-9033c37ccf394abe97f48021c393cc56)
* **Woman:** [Sketchfab Link](https://sketchfab.com/3d-models/person-169f0d46b96d4d5ab84a5307a0d4da60)
* **Additional Character:** [Sketchfab Link](https://sketchfab.com/3d-models/person-7beba61fc6464b528067cdd1282b38d3)
* **Laptop:** [Sketchfab Link](https://sketchfab.com/3d-models/laptop-7d870e900889481395b4a575b9fa8c3e)

## The Process
To build this application, we started by measuring and modeling our physical AR/VR/MR classroom to recreate it in the Unity game engine. The project is organized into clear sections: Scenes for the room layout, Prefabs for reusable objects like furniture, and C# Scripts to handle how users move and interact. 

We used the Meta XR SDK to ensure the app works perfectly with Quest headsets and the Universal Render Pipeline (URP) to keep the visuals high-quality without slowing down the performance. To make the space feel more natural, we integrated MetaHumans to represent the people in the room.

### How to Run
1. Open the project folder in Unity.
2. Ensure you have the necessary Meta packages installed via the Package Manager.
3. Connect your Meta Quest headset.
4. You can use the Play button in the editor for a quick test or build an APK file to install the application directly onto the device.

## Challenges & Future Work
Building this project came with several hurdles, primarily involving the Meta Quest hardware. For a large portion of the development time, the headset was not working correctly, which made it very difficult to test features in real-time. We ran into numerous technical issues with the initial setup, from connection bugs to software version mismatches. These challenges taught us a lot about troubleshooting hardware-software integration and the importance of a solid testing plan.

Because of these setbacks, there wasn't quite enough time to build everything we envisioned. In the future, we hope to:
* Add interactive classroom elements like a working whiteboard.
* Enable multiplayer support for multiple users to join the same session.
* Improve MetaHuman animations to make the virtual students look even more lifelike.

## AI Usage & Collaboration
Throughout the development of this project, we used ChatGPT to help navigate the initial setup and configuration phases. Since Meta Quest integration can be complex, we relied on AI to troubleshoot error messages and clarify the specific steps needed to get the Unity environment communicating with the headset. This was especially helpful for identifying compatible SDK versions and fixing common bugs during the installation process.

## Demo Link
https://youtu.be/hZ7G8vUNeX0
