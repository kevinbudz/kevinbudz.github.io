# Adding your server to Realmdex.
> Everything needed to add your server can be done by requesting to edit `global.json`, details for what each field means are listed below. As well as an empty template for you to copy/paste.
```json
    {
      "id": "utr", // usually an acronym of your server.
      "title": "UT Reborn", // the full title of your server.
      "description": "© kevinbudz, 2024.", // i just attach my name here, up to you.
      "version": "4.01", // current game version.
      "urls": {
        "swf": "https://kevinbudz.github.io/utr/client.swf", // URL to client's .swf.
        "air": "https://kevinbudz.github.io/utr/client.zip" // URL to the AIR package, realmdex extracts the .zip inside of app.
      },
      "banner": "https://kevinbudz.github.io/utr/banner.png", // banner that displays in ServerList.
      "altBanner": "https://kevinbudz.github.io/utr/banner.png", // banner that displays in Downloads.
	  "playerCountUrl": "http://157.173.195.91:8080/app/getPlayers", // this is a URL that returns ONLY the amount of people that are online.
	  "discordLink": "https://discord.gg/utr", // attach a discord link.
	  "executable": "UT Realms.exe" // <-----
       /* this is a headache to explain, if you download
       the .zips for both UTR and Attack the Boss, you will
       see why these fields are listed the way they are. */
    },
```
**↑ use the scrollbar!!!**
## Empty template:
> Make sure you account for any commas or any brackets that need to be added/removed.
```json
    {
      "id": "rotmg",
      "title": "",
      "description": "©",
      "version": "1.0.0",
      "urls": {
        "swf": "",
        "air": ""
      },
      "banner": "",
      "altBanner": "",
	  "playerCountUrl": "",
	  "discordLink": "",
	  "executable": ""
    },
```
