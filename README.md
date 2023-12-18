<div align="center">
  
  ![eye](https://github.com/Dismalitie/Doxel/assets/118924562/f2fcb86f-9b32-4c6e-8233-ed6386a94bca)



  # Doxel

 Local Machine Network and Hardware testing tool
</div>

## How do I use this?
**This is a CLI application.** Download all `dll` and `exe` files in the [`bin` directory](https://github.com/Dismalitie/Doxel/tree/main/Doxel/bin/Debug) to a folder. Then run the application with an argument to a Discord Webhook Link:
```ini
Doxel.exe [URL_HERE]
```
Doxel will return an embed looking like this:

![image](https://github.com/Dismalitie/Doxel/assets/118924562/47c63024-9a3d-479f-b063-eb8edbc74b92)

or something like this if it experienced an error somewhere:

![image](https://github.com/Dismalitie/Doxel/assets/118924562/9d38b5b5-8875-49ae-9efb-ce4edd354507)

This embed will gather all the info **from the machine it was run from.** So be cautious of running it with args on accident.

The executable can be embeded in some other app and run when called.


# Network

* IP
* Country
* Region
* City
* Coordinates
* ISP

*+ Raw JSON output, e.g:*
```json
{"status":"success","country":"United States","countryCode":"US","region":"VA","regionName":"Virginia","city":"Ashburn","zip":"20149","lat":39.03,"lon":-77.5,"timezone":"America/New_York","isp":"Google LLC","org":"Google Public DNS","as":"AS15169 Google LLC","query":"8.8.8.8"}
```

# Hardware

* Machine Name
* OS Version
* Processors
* Architecture
* Processor
