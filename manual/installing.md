# Installing & Updating

## Installation

Download and import plugin unitypackage from the Asset Store. After installation all plugin components it will be located in `%ProjectFolder%/Assets/uNode` folder. Plugin options will be located in `%ProjectFolder%/uNodeData` folder.

> [!IMPORTANT]
> After importing uNode whether you first install or updating you will need to restart Unity Editor to properly initialize uNode.

> [!NOTE]
> uNode includes some additional `System.*.dll` and `Microsoft.CodeAnalysis.dll` libraries that originally provides in NuGet. They are located under `uNode3/Plugins/Roslyn`. If other packages use these libraries (e.g. Unity Collections package using System.Runtime.CompilerServices.Unsafe.dll), to avoid conflicts, please delete the DLL under `uNode3/Plugins/Roslyn`.

## Updating uNode

If you are updating or re-installing uNode into a Unity project where uNode was already being used, it is recommended that you perform a clean re-install of uNode as detailed below.

> [!IMPORTANT]
> Please be sure you have fully backed up your Unity project before attempting any updates!

### Performing a Clean Re-Install of uNode

A clean re-install is when you delete the root uNode folder before importing the latest uNode.unitypackage file into your Unity project.

This is the recommended way to update uNode because we may have changed or deleted old files and Unity’s package system will not remove files when installing a new package over an old one. This can lead to old or conflicting files that can cause issues.

Please follow these steps to do a clean re-install:

- Load your Unity project(s) using uNode and delete the root “uNode” folder in your “Project” tab by right-clicking it and selecting “Delete” from the context pop-up menu.
- You can now re-install uNode.
