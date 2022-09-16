# Photon Charge ALPHA TEST-How To Set Up

```
Make Sure You Have Photon Pun installed and the CORRECT AppID in the server settings .
Then make an empty GameObject Call it "PhotonChargeManager" then add the PhotonChargeManager Component to the gameobject.
After it is added change the maxplayers per room and also make sure to set the transforms RightHand, LeftHand, Head
```

> Head-Main Camera

> RightHand-RightHand Controller

> LeftHand-LeftHand Controller

# Photon Charge

### Make sure to use this namespace
        
``` using Photon.Charge; ```
        
### Player Settings
        
```PhotonChargeManager.SwitchName("PlayerName");```

```PhotonChargeManager.ChangeColor(new Color(0,0,0));```

```PhotonChargeManager.ChangeSecondaryColor(new Color(0,0,0));```

```PhotonChargeManager.ConnectToServerOnStart();```

### Rooms/Servers

```PhotonChargeManager.JoinPrivate("RoomCode", MaxPlayers);```

```PhotonChargeManager.JoinSolo("RoomCode");```

```PhotonChargeManager.DisconnectFromMultiplayer();```

### Cosmetics

```PhotonChargeManager.EnableCosmetics("CosmeticName");```

```PhotonChargeManager.DisableCosmetics("CosmeticName");```

### Cosmetics That Don't Save

```PhotonChargeManager.TempEnableCosmetic("CosmeticName");```

```PhotonChargeManager.TempDisableCosmetic("CosmeticName");```

 ###  Send All Players RPCS

```PhotonChargeManager.SendAllPlayersAnRPC("RpcName");```

 ### Send All Players RPCS While Your Master

```PhotonChargeManager.SendAllPlayersAnRPCWhileMaster("RpcName");```

 ### Give Random Teams Using RPCS

```PhotonChargeManager.GiveTeam("RedRPC", "BlueRPC");```

 ### Instantiate Object Across The Network

```PhotonChargeManager.Instantiate("ObjectName");```

 ### Server/Room Info

```string LeaderboardDisplayer = PhotonChargeManager.LeaderBoard;```

```string CurrentPlayersInRoomCounterAsString = PhotonChargeManager.PlayersInRoom().ToString();```

```int CurrentPlayersInRoomCounterAsInt = PhotonChargeManager.PlayersInRoom();```

```string PlayersOnlineAsAString = PhotonChargeManager.PlayersOnline().ToString();```

```int PlayersOnlineAsAInt = PhotonChargeManager.PlayersOnline();```

```string RoomsAsAString = PhotonChargeManager.CurrentAmountOfRooms().ToString();```

```int RoomsAsAInt = PhotonChargeManager.CurrentAmountOfRooms();```
    
# Photon Charge Offline
### Make sure to use this namespace
        
```using Photon.Charge.Offline;```
        
   ###     ChangePlayerName While Offline
```PhotonChargeOffline.ChangeNameWhileOffline("PlayerName");```
        
   ###     Change Colors While Offline
```PhotonChargeManager.ChangeSecondaryColorWhileOffline(new Color(0,0,0));```

```PhotonChargeOffline.ChangeColorWhileOffline(new Color(0,0,0));```

  ###      Enable And Disables Cosmetics While Offline
```PhotonChargeOffline.DisableCosmeticWhileOffline("CosmeticName");```

```PhotonChargeOffline.EnableCosmeticWhileOffline("CosmeticName");```

#   Questions & Socials
`
If you have ANY questions join the discord:
`
[Discord](https://discord.gg/9wjCKv4xfq)

`
My tiktok:
`
[TikTok](https://www.tiktok.com/@gotyohat_dev?is_from_webapp=1&sender_device=pc)
