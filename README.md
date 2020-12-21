DepotDownloader.Library
===============

Steam depot downloader utilizing the SteamKit2 library, but as a library.

### Downloading one depot

```c#
AccountSettingsStore.LoadFromFile("account.config");
ContentDownloader.InitializeSteam3();

ContentDownloader.DownloadAppAsync(<appId>, <depotId>, [manifestId]);
```