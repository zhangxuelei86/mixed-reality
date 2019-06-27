## Adding an Offline mode for local speech-to-text translation

In this lesson, we'll add an Offline mode that lets you perform local speech-to-text translation when we are unable to connect to the Azure service. We will also *simulate* a disconnected state.

1. Select the Lunarcom_Base object in the hierarchy, and click Add Component in the Inspector panel. Search for and select the Lunarcom Offline Recognition.

![Module4Chapter2step1im](images/module4chapter2step1im.PNG)



2. Click the drop-down in the LunarcomOfflineRecognizer, and select Enabled. This programs the project to act like the user doesn't have a  connection. 

![Module4Chapter2step1im](images/module4chapter2step2im.PNG)

3. Now, press play in Unity Editor, and test it. Press the microphone in the bottom left hand corner in the scene, and begin speaking. 

> Note: because we’re offline, wake word functionality has been disabled. You'll have to physically click the microphone every time you wish to have your speech recognized when offline. 

Below is an example of what your scene could look like.

![Module4Chapter2exampleim](images/module4chapter2exampleim.PNG)

## Congratulations

The offline mode has been enabled. Now, when you're offline, you can still work on your project with the speech-SDK! 

[Next Lesson: SpeechSDK Lesson 3](link placeholder)
