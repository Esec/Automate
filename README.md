# Automate

![](http://i.imgur.com/5FMVk0u.png)

# Compiling

Seems successfully compiled on Visual Studio 2019 without touching any code.
1. Download this project and `ShareX/ShareX/releases/v11.5.0`. The similar date when this project last modified.
2. Extract `Automate` and pull `ShareX.HelpersLib` folder out. Place them like
~~~~
root/
  Automate/
  ShareX/
    ShareX.HelpersLib/
~~~~
3. Launch `Automate.sln` under Automate/. VS2019 should show no error now before hitting compile.
4. Right click `ShareX.HelpersLib` and manage NuGet. I updated Newtonsoft.Json to 12.0.3 and it works fine. If latest version doesn't compile. Just rollback to it's default version.
5. Hit the play button and it's working for me.
