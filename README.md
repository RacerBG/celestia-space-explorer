# Celestia Space Explorer – A spacecraft cockpit add-on for Celestia

## About
It transforms the traditional planetarium experience into a first-person space exploration experience by adding a 2D spacecraft cockpit, engine sound effects and custom navigation behavior. The add-on does not attempt to simulate spacecraft physics or replace the original planetarium functionality.

## Features
- **2D Cockpit Overlay**: Adds a custom spacecraft cockpit directly over Celestia's 3D environment.
- **Sound Effects**: Provides audio feedback for spacecraft navigation, with separate sounds for the main engine and secondary thrusters.
- **Dynamic Travel Time**: Travel duration dynamically adjusts according to the distance of the selected object, from 3 to 60 seconds.
- **Smooth Object Centering**: Centers selected objects using a transition duration of 3 seconds.
- **Custom Navigation Messages**: Displays the destination and current navigation status.
- **Mouse Navigation**: Preserves mouse-based camera navigation while disabling right-click context menus.

## Requirements
- Celestia 1.7.0
- Lua scripting support
- Audio playback support for WAV files

## Installation
1. Download the latest release from the [Releases](https://github.com/RacerBG/celestia-space-explorer/releases) page (or clone the repository).
2. Extract the add-on files into a directory of your choice.
3. Keep the CELX script and all required resource files together in the same directory.
4. Launch the CELX script from Celestia's `Open Script...` menu.

## Compatibility
Celestia Space Explorer is designed for Celestia 1.7.0 and uses its native CELX scripting API. Audio playback depends on the audio capabilities of the Celestia build.

## Credits
Thanks to the Pioneer Space Simulator team for the sounds!

## License
This project is licensed under the GNU General Public License v3.0 – see the [LICENSE](LICENSE) file for details.

## Author
- Georgi Georgiev (RacerBG)
