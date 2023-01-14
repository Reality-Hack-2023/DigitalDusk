# REPO-029 aka _Digital Dusk_
A VR-forward sunset generator built in Unreal Engine 5, with Esri global data integration, and (ongoing) multiuser functionality.

## Environment Setup
- Install the [Epic Games Launcher](https://www.unrealengine.com/en-US/download)
- Create an Epic Games account to sign in to their ecosystem.
- Install Unreal Engine 5.1.0
- Launch 5.1.0, upgrading .NET and NVIDIA drivers if prompted.
- Install the [Oculus App](https://www.meta.com/quest/setup/)
- Create a Meta account to sign in to their ecosystem.
- Install [Android Studio](https://developer.android.com/studio) (We used the version "Electric Eel | 2022.1.1" but newer may work)
- Install the Android 10 SDK (solution)[https://forums.unrealengine.com/t/solved-sdk-ndk-and-jdk-configuration-for-compiling-android-including-oculus-quest-2-for-26-2-and-27-2/587171]

## Troubleshooting
- Ensure that your headset is connected in the Oculus Link app within the headset, before running the UE5 project.
- In the Oculus Desktop app, make sure the headset is set to default for OpenXR Runtime.
- Enable the toggle for Unknown Sources.
- In the Beta tab, toggle on the Public Test Channel.
- In Unreal, did you select VR Preview as the viewing mode? (Triple dots next to play buttons)
