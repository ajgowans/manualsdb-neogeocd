# The MiSTer Manuals DB - Neo Geo CD

This is a database for the MiSTer project that downloads the English manuals in .pdf form for the Neo Geo CD to the docs folder, which can be loaded from the OSD within th core by selecting "Help".

To use it simply copy and paste the below to the bottom of your downloader.ini file (found at: /media/fat/downloader.ini )

```ini
[ajgowans/manualsdb-neogeocd]
db_url = https://raw.githubusercontent.com/ajgowans/manualsdb-neogeocd/db/db.json.zip
```
