# Teufelswerk's Audio Device Switch [ts-audio-device-switch]

This Teamspeak 3 plugin adds a new Option to switch the audio device for a specific user. The idea was born on the roleplay GTA V server StateV. Where a small group of outlaws teamed up with the Teufel company (Ingame) to work together to counter music copyright issues.

**[Update: 18.12.2020 First functional prototype. Busy to create documentation, stay tuned!]**

Introduction (German): https://www.youtube.com/watch?v=kJ1D4hwM8ZE 

**Any contribution is very welcome!**

## Idea

A Option to switch the audio device for a specific user by right click on the user name.
Use case example: In some games users will play copyright protected music. With this feature for example a streamer can split these audio streams into another. Then its possible to hear the music but not record or stream them.

![alt tag](https://github.com/jonasesser/ts-audio-device-switch/blob/main/docs/pics/idea.PNG)

![alt tag](https://github.com/jonasesser/ts-audio-device-switch/blob/main/docs/pics/Voicemeeter%20Example.png)


## Screenshots

### Client context menu
To switch the playback profile for a specific user/client -> right click on username > Teufelswerk's Audio Device Switch > Click on Playback Profile.

![alt tag](https://github.com/jonasesser/ts-audio-device-switch/blob/main/docs/pics/ts_client_menu.png)


## Installation of prototype []

The Installation of the first prototype version is still complex, but will be simplified in the final version.

1.  Download and Install the plugin that fits to your system

[ts-audio-device-switch 32Bit](https://github.com/jonasesser/ts-audio-device-switch/blob/main/package/release/ts-audio-device-switch_32Bit.ts3_plugin)
[ts-audio-device-switch 64Bit](https://github.com/jonasesser/ts-audio-device-switch/blob/main/package/release/ts-audio-device-switch_64Bit.ts3_plugin)

2.  Download and Install Voicemeeter Banana (Free Version) or Voicemeeter Potato

[Voicemeeter Banana](https://vb-audio.com/Voicemeeter/banana.htm)
[Voicemeeter Potato](https://vb-audio.com/Voicemeeter/potato.htm)

3.  Activate 7.1 Surround Sound for each Voicemeeter Input Device

    (screenshot)

4.  Configure TeamSpeak

    a. Select as playback Device **VoiceMeeter VAIO 3 Input (VB-Audio VoiceMeeter VAIO3)**
    b. Select **Mono Sound Expansion** > **Mono to surround (if available)**

    (screenshot)

5. Configure Voicemeeter Banana

    a. On the **VAIO 3** Input activate Output **B1** and **B3**
    b. In the **Master Section** select for **B3**: **MIX down A** and **mono**
    
    (screenshot)

6. Configure OBS

    a. Select each Voicemeeter Output as Audio Device (MIC/Aux Device 1 to 3)
    b. Mute the **VOIO3 Output** 

    (screenshot)


