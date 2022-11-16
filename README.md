
# Additional Palettes for MiSTer's Game Boy ore.

This is a Database that will help you install a few extra palettes for your Game Boy core in [MiSTer FPGA](https://github.com/MiSTer-devel).

### How to Install

Add an entry to the `downloader.ini` file on the root of your SD (create it if it doesn't exist), to use it with the [MiSTer Downloader](https://github.com/MiSTer-devel/Downloader_MiSTer/) (which is what Update All calls under the hood). For that, please add the following entry there:

```
[ZReport/gameboy-palettes]
db_url = https://raw.githubusercontent.com/ZReport/gameboy-palettes/db/db.json.zip
```

Once you've done this, the palettes will be installed upon running the downloader again.
