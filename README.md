# (FIFA SOCCER 08 NDS Exploit)
<img src="https://i.imgur.com/v23exIs.jpg" width="320">
A successful attempt to exploit the game US version of FIFA SOCCER 08 for the Nintendo DS to execute unsigned code from the savegame.

* This runs in a NTR-mode so nothing much can be done in that environment but run a very small payload within the save.

## Usage (Patching the savefile)
* Win32: `CRCFix SoccerPwn08.sav`
* Linux: `./CRCFix SoccerPwn08.sav`
###
## Triggering the exploit
Navigate to "My FIFA 08" then go to "My Profile", PWN'D
###
## Special thanks to:
* jerbear64 (testing the exploits on retail for US/EUR users)
* CTurt (Originally exploited the EUR version)
###
## Support:
* Supports both US & EUR versions of the game.
* Works with emulators. (desmume, no$gba, srloader, etc.)
###
## Requirements:
* A copy of the "FIFA SOCCER 08/FIFA 08"
* Any DS that's in the DS family.
* A way to inject the save. (I'd use TWLSaveTool on the 3DS, you'll need CFW on your 3DS. GodMode9 is an option as well)