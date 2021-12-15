# Crod vr room unity integration
This package allows you to integrate into your unity§ project the capabilities of the multi-media hall at the CROD 

### Requirements
- Unity 2019.4 or newer
- DirectX12 enabled in project

### How to install
1. Download prefab.unitypackage from releases page (https://github.com/ltd-profit/crod-vr-room-unity-integration/releases)
2. Open your Unity project
3. Open downloaded file
4. Import all files in Unity

### How to use
Just drag VrCaveCamera prefab to your scene

### Troubleshooting
- Problem: 
Some displays not working in room
- Solution: 
Check if DirectX12 enabled in your project:
1. Open Player settings (Edit -> Project Settings... -> Player)
2. Disable "Auto Graphics API for Windows"
3. Add Direct3D12 to list below
4. Drag it to the top of the list
5. Save and Restart

![image](https://user-images.githubusercontent.com/38568293/146192491-e31ce095-4eaa-4a32-a3ac-6bee2176800c.png)
