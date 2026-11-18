# Lucky Stars Champions

Created by **River-Sage**.

This repository contains the clean Windows distributable for **Lucky Stars Champions v5.1.38-r334**, an unofficial fan modification of *Yu-Gi-Oh! Forbidden Memories* (USA).

## Create the game image

1. Download or clone this repository.
2. Put your own legally obtained USA retail BIN in `Place_Vanilla_Rom_Here`.
3. Run `Create_Champions.exe` from the repository root.
4. After the builder reports success, launch `Champions/Champions.cue` in your emulator.

The builder validates the source image, patch, and finished image. If it reports an error, check `Last_Run_Log.txt` beside the EXE. The required retail disc is SLUS-01411, raw single-track MODE2/2352, 517,872,768 bytes, with this SHA-256:

```text
6e22494a45bf50fa2d239cd3819a57163a5f9b91e0365babc3e101509b5c3a7c
```

Open `2_READ_ME_GAMEPLAY.html` for the gameplay guide. Drop tables, enemy decks, combo information, and farming guides are in the `Champions` folder.

## Legal and content notice

This clean distributor contains only original documentation, Windows builder programs, and compressed XOR delta data. It contains no retail or prebuilt game image and requires users to supply their own legally obtained exact retail image.

*Yu-Gi-Oh!* and related marks belong to their respective owners.

## License

The original work in this repository is available under the [MIT License](LICENSE). You may use, copy, modify, publish, and redistribute it, provided the copyright and license notice crediting River-Sage is retained.
