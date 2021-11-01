# Outlast Hero Model

**Model**: Chris Walker \
**State**: Draft Version (Bad) \
**Shadow State**: Missing Head \
**Archive Size**: Normal (Uploaded here)

**Screenshots**:

![](https://i.imgur.com/xZy2B3g.png)
![](https://i.imgur.com/CryLvYX.png)
![](https://i.imgur.com/vaemZyL.png)

# How install this?

Need Outlast: **https://store.steampowered.com/app/238320/Outlast**

1. Download repository: ``git clone https://github.com/ShyKiss/outlast-hero-model-chriswalker.git``

2. Download: **https://drive.google.com/file/d/1WEkB2Ii57aBixD_MokSW9L2R6T4zLEtm/view**

3. Download: **https://www.dropbox.com/s/jd0q9f3mc74jxmv/Level_Launcher.Bat**

4. Drop OLCustomPlayerModelSDK.u in **[Outlast Dir]**/OLGame/CookedPCConsole

5. Change lines in **[Outlast Dir]**/OLGame/Config/DefaultGame.ini

      **Replace:** \
         DefaultGame=OLGame.OLGame \
         DefaultServerGame=OLGame.OLGame \
         PlayerControllerClassName=OLGame.OLPlayerController \
         DefaultGameType="OLGame.OLGame"

      **To:** \
         DefaultGame=OLCustomPlayerModelSDK.OLCustomGame \
         DefaultServerGame=OLCustomPlayerModelSDK.OLCustomGame \
         PlayerControllerClassName=OLGame.OLPlayerController \
         DefaultGameType="OLCustomPlayerModelSDK.OLCustomGame"


6. Drop Level_Launcher.bat in **[Outlast Dir]** and open it.

7. Clone this repository and extract "ChrisPM" folder in **[Outlast Dir]**/PlayerModels

8. Type in Level_Launcher.bat command line: ``mount [Model Folder Name]`` \
   Example: ``mount ChrisPM``
   
9. Start Outlast.

# How update this?

Update repository: ``git fetch https://github.com/ShyKiss/outlast-hero-model-chriswalker.git``

# Creators

Level Launcher and SDK: superboo07 (**https://github.com/superboo07**) \
Model: Beerymaid (Me)

Outlast Modding Community: **https://discord.gg/rj55WY2JDP**
