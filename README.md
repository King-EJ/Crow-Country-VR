# Crow-Country-VR
VR mod for Crow Country  "test builld"


<img width="1254" height="1254" alt="Crow Country VR Ticket Booth" src="https://github.com/user-attachments/assets/7cb671ef-a47a-49d2-8a5b-4168b311fd4c" />



CROW COUNTRY VR  -  VR mod (Unity 2022.3.49, Mono x64, built-in renderer, BepInEx 5)
=====================================================================================
Version 0.1.12 (test build)

INSTALL
  1. 

  
VIEW
  * Third person (default): you stand where the game's camera is; when it turns or cuts your view turns with it.
  * First person: Mara's eyes, her head hidden. The left stick walks where you look, the right stick turns you.
  * RIGHT STICK CLICK (R3) = switch first / third person.
  * RIGHT STICK DOWN = third person Follow (behind Mara; the right stick turns you, the left stick walks where you
    look) / GameCamera (at the game's camera).
  * Menus / pause / inventory / map: the game's picture on a screen in front of you, plain Xbox controls.

ARMS (first person)
  * Mara's arms follow your controllers, her hands (and the gun) turn with them.
  * LIVE ARM ADJUST: hold X 1 s - the hands stay where they are in the air; move your controllers to where you
    want to hold them, then press X to keep it (saved).
  * Her arms get longer when your controller is further than she reaches ([Arms] ArmsReachController).
  * VR settings menu "Arms": arm size, LEFT / RIGHT hand position (left / right, up / down, forward / back), hand
    turn. Config: [Arms] ArmSize, LeftHandPosition, RightHandPosition, HandRotation.

AIM
  * 6DOF aim (first person): while you aim (right grip) Mara aims where your right controller points - left / right
    and up / down (the mod steers the game's own up / down aim; wrong way: [Aim] UpDownInvert). Third person aims
    like the normal game ([Aim] SixDofInThirdPerson to change).
  * Laser from the right controller: RIGHT STICK UP turns it on / off (game has own laser also).

CONTROLS (the VR controllers are an Xbox 360 controller for the game)
  Left stick ............ left stick
  
  Right stick ......... third person: right stick; first person: turn
  
  Right trigger ....... RT (shoot)
  
  Right grip ............ LT (aim)
  
  Left trigger ........ RB
  
  (swapped: [Controls] SwapRightGripAndLT)
  
  Left grip ............. Y
  
  Y button ............ LB
  
  (swapped: [Controls] SwapLeftGripAndY)
  
  Left stick click ...... START (tap) / BACK (hold 0.6 s)
  
  Right stick click ..... first / third person (menus: R3)
  
  Right stick up ........ laser on / off
  
  **Right stick down ...... third person Follow / GameCamera**
  
  Both stick clicks ..... re-centre (hold 1.2 s = VR settings menu)


Disable: to disable Mod rename winhttp.dll to winhttp.dll.bak

[VR Mod Manager](https://github.com/King-EJ/VR-Mod-Manager/releases/tag/VRModManager)

LICENSES
-
Uses Astien's OpenXR bridge. Free, non-commercial.
