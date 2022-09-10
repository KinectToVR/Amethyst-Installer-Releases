# Amethyst Installer Releases

Amethyst is a Windows application for using various devices for body tracking in virtual reality (Specifically in SteamVR). It can be [extended with user-made plugins](https://github.com/KinectToVR/K2TrackingDevice-Samples) to support any device you wish.

This is a rewrite from the ground up, it is *not* based on KinectToVR/K2EX. It is a whole new app that doesn't carry the legacy baggage of K2EX. We were able to fix numerous bugs and streamline the experience. We hope you will enjoy it. If you like what you see and you wish to support future development, you can throw money at us with the [<img style="display:inline; height:26px;" src="https://user-images.githubusercontent.com/8508676/189487326-eff20178-77a2-4ea4-9798-d389e53501e4.png">](https://opencollective.com/k2vr) button.
  (We won't force you, though every expense is currently out of pocket.)

---

This repository holds the published releases for Amethyst Installer.

![image](https://user-images.githubusercontent.com/8508676/188240306-5e8e048c-c150-4925-9616-ccbd8db0267f.png)
<details>
<summary>More screenshots</summary>

![image](https://user-images.githubusercontent.com/8508676/188240512-c986f784-74b4-4511-9e7d-6cf17c408f55.png)

![image](https://user-images.githubusercontent.com/8508676/188240521-36a23a94-4a83-4760-9cde-6a3b8cf234e8.png)

![image](https://user-images.githubusercontent.com/8508676/188240529-7cd6632d-4ef3-4747-a69b-2bdb50afd0d3.png)

![image](https://user-images.githubusercontent.com/8508676/188240541-88b5e753-a63f-421f-b0e0-cb7c5df3f1fa.png)

![image](https://user-images.githubusercontent.com/8508676/188240570-caa46c3f-923e-4f25-a219-dc4c3e2ccbce.png)

</details>

## Setup

Download the latest release and run it. No really, it's that simple.

[Amethyst's pre-requisites still apply here.](https://github.com/KinectToVR/Amethyst-Releases#pre-requisites-you-need-these-to-run-the-app)

### I ran the setup but it didn't work!

- You have most likely encountered a bug, or, your setup is unsupported.

- If you believe that you have encountered a bug:
  
  - Join our [Discord server](https://discord.gg/YBQCRDG), or open an issue on this repository.
  
  - Describe the bug.
  
  - Describe what you did to encounter the bug
  
  - Send us your log files. You can find them by clicking the "View logs" button, then click the file path. The currently generated log file will also be selected, so that you can simply drag and drop it to us.
  
## What can it do?

A long list of things this installer can do (or we're planning on making it do later):

- Installing Amethyst.
- Installing the Kinect for Windows 360 SDK and Toolkit silently.
- `HttpClient` downloader with timeout support, and MD5 checksum verification (and optional caching, only in dev builds).
- `amethyst://` protocol links. These are currently undocumented.
- A multi-threaded sound engine that supports up to 8 voices.
- Custom WPF theme to bring the look and feel of WinUI3 to WPF.
- Debug system.
- Automagic fixes for common errors (most notably E_NUI_NOTPOWERED).
- Detecting SteamVR setup automatically.
- More stuff we have in the works.

## Source Code

Due the app's current state, I have decided to hide the source code until the app is finished.  
If you really want it though, please ask us in the K2VR Community Discord.


