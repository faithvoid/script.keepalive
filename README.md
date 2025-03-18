# KeepAlive
Quick and dirty Python Interpreter speed hack for XBMC4Xbox. Uses a LOT of RAM as the interpreter will always be on, recommended only for 128MB Xbox systems!

## How To Install
- Copy to "Q:/scripts/KeepAlive"
- Select "KeepAlive" from the Scripts menu
- ???
- Profit!
- Scripts and add-ons should load faster from this point on.

## Bugs:
- This along with the interpreter uses about 10MB of RAM by default. As XBMC has about 32 or so megabytes of free RAM left at startup, this can cause issues.
- This extra RAM usage can cause the system to crash when watching videos or doing other RAM-intensive tasks.
- This can possibly cause interference with other scripts. It shouldn't, but there are bugs with how certain Python scripts handle things such as threading that can cause issues with multiple scripts running at once.
