# ChangeScreenResolution
Powershell script to change screen resolution on Windows

### Installation
```
Install-Module ChangeScreenResolution
```
### Parameters
* Width: Define the width of the new screen resolution
* Height: Define the Height of the new screen resolution

### Examples
```
    Set-ScreenResolution 1920 1080
    # To run in a remote session (Enter-PSSession)
    Set-ScreenResolution 1600 900 -AsTask
    
```
