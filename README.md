
# Additional Palettes for MiSTer's Gameboy core

This is a Database that will help you install a few extra palettes for your Gameboy core in [MiSTer FPGA](https://github.com/MiSTer-devel).

### How to install

Add an entry to the `downloader.ini` file on the root of your SD (create it if it doesn't exist), to use it with the [MiSTer Downloader](https://github.com/MiSTer-devel/Downloader_MiSTer/) (which is what Update All calls under the hood). For that, please add the following entry there:

```
[ZReport/gameboy-palettes]
db_url = https://raw.githubusercontent.com/ZReport/gameboy-palettes/db/bios_db.json
```

Once you've done this, next time you run downloader, the palettes will get installed too.
