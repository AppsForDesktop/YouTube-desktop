# YouTube for desktop

YouTube for desktop is the same YouTube but for Windows as desktop application

YouTube windows is a video sharing service where you can watch, like, share, comment and upload ypur own videos.
The video service can be accessed on PCs, laptops, tablets and via mobile phones by using apps.

 
1.   In YouTube desktop you can: 
     - Users can search for and watch videos
     - Create a personal YouTube channel
     - Upload videos to your channel
     - Like/Comment/share other YouTube videos
     - Users can subscribe/follow other YouTube channels and users
     - Create playlists to organize videos and group videos together
     
2.   Perks of having YouTube windows App:
     - An icon on your quick access spots
     - One-click launch
     - No need for an open browser tab

YouTube desktop works on Windos 7, Widows 8, Windows 10, Windows 11.

What are you waiting for? Hit Download and open up YouTube App on your Windows platform Desktop or Laptop.

## Installation

You can install YouTube desktop on Windows by running the installer of latest [release](https://github.com/AppsForDesktop/YouTube-desktop/releases/download/1.0.0/YouTube.desktop.install.exe).

## Usage

Run the "YouTube.desktop.install.exe" and follow installation instructions.

## For professionals

3.   You can build whole application from source code. For that you will need:
     - Visual studio 2019 with support to build .NET Framework 4.6
     - If you would like to create such installer as in release, you will need NSIS 2.5.1.

Run Developer Command Prompt for VS 2019

Execute commands in this prompt:

```
msbuild "YouTube desktop\YouTube desktop.sln" /p:Configuration=Release /p:SelfContained=True /p:PackageAsSingleFile=true /t:Publish /p:PublishDir=Publish

makensis installer_script.nsi
```


## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.
