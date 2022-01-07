# framework-arduinoteensy-rsr

Minimal Teensyduino framework for PlatformIO with addional USB device definitions.

Unlike stock framework package, only platform-specific libraries that are not available on PlatformIO's main repository are included in the `libraries` directory. More can be added easily when required (as long as they are git repositories).

Arduino-specific TXTs (i.e. `keywords.txt`, `boards.txt` and `platform.txt`) are not included due to them not being used in PlatformIO's build script. 