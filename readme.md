# flipper

Hello World app for the Flipper Zero.

## Build

Requires [ufbt](https://github.com/flipperdevices/flipperzero-ufbt) (`pip3 install --user ufbt`).

```sh
ufbt        # builds dist/hello_world.fap
```

## Install on the Flipper

Connect the Flipper via USB, then:

```sh
ufbt launch # uploads the .fap and starts it on the device
```

Or copy `dist/hello_world.fap` to the SD card under `apps/Misc/`.
The app shows up on the device under **Apps → Misc → Hello World**.
