SteamWorks
==========

Exposing SteamWorks functions to SourcePawn.

How to find the corresponding steamworks_sdk ?

Go to https://partner.steamgames.com/downloads/list and search for the binary libsteam_api.so that matches the output of the symbols with the following command:
```nm -gD libsteam_api.so | grep -i "something different between libsteam_api versions"```

Current SteamWorks version => 28 jui 2015	1.34
