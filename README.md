# mojan

Visual novel about mahjong made in 4 months with about 1000 lines of dialogue and ~1 hour of content.

## Running it

There is no packaged release; the game runs from source with the [Ren'Py SDK](https://www.renpy.org/release/8.2.1) (written against 8.2.1).

1. Download and unpack the SDK.
2. Launch a build folder with it: `renpy.sh b8` on Linux or macOS, `renpy.exe b8` on Windows. Or point the launcher's projects directory at this repository and pick `b8`.

`renpy.sh b8 lint` checks the scripts without opening the game.

## Layout

`b1` to `b8` are successive snapshots of the whole project; `b8` is the latest and the one to play or edit. Inside `b8`:

| Path | Contents |
|---|---|
| `game/script.rpy` | Story and dialogue |
| `game/items/` | Inventory, crafting, shop and quest screens |
| `game/screens.rpy`, `game/gui.rpy`, `game/options.rpy` | Interface and project settings |
| `game/images/`, `game/gui/` | Art and interface assets |

## Credits

Developed by Kaelan Yim and Jaden Lee. Art by Kendall Lee. Storyboard by Nora Millward.

## Screenshots

![image](https://github.com/user-attachments/assets/b4153134-de3f-42c1-8228-fa8ae076c36a)
![2024-11-13-00-12-45_mojan_C9hUEiL3Df](https://github.com/user-attachments/assets/594c5b89-ebe8-4622-b735-a523b304849b)
![2024-11-13-00-10-44_mojan_x50cqk3zPu](https://github.com/user-attachments/assets/ec239de3-ae35-4675-a322-c0e8f855cf0a)
![2024-11-13-00-09-12_mojan_TBF46b2kr5](https://github.com/user-attachments/assets/4f73e983-c58a-4f82-b01e-7a16f4192bbf)
![2024-11-13-00-10-06_mojan_5qfxSRVy2S](https://github.com/user-attachments/assets/41ce72a1-d368-47d5-aa5b-523130ba2527)
![2024-11-13-00-08-32_mojan_otKEHFyMF8](https://github.com/user-attachments/assets/8263dd50-9531-406d-9c12-083421441535)
![2024-11-13-00-09-51_mojan_iDnoMiceAh](https://github.com/user-attachments/assets/057b283c-49dd-4ff4-a2ec-d06b0c1726b3)
