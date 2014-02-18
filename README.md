# Skipstone

Skipstone is a fully featured universal media player remote watch app for the Pebble Smartwatch to control media players such as Plex, VLC, and XBMC.

### Table of Contents
* [Plex](#plex)
* [VLC](#vlc)
* [XBMC](#xbmc)
* [Release Notes](#release-notes)
* [License](#license)

## Plex

### Features

* List all clients connected to the Plex server and control any of them.
* Toggle play/pause.
* Press select, back, up, down, left, and right buttons.
* Short and long step forward/backward.

### Controls

| Button                                               | Function                      |
| ---------------------------------------------------- | ----------------------------- |
| Long click select                                    | Switch between options 1/2    |
| Double click select                                  | Back Button                   |
|                                                      |                               |
| Single click select <sub><sup>(option 1)</sup></sub> | Select Button                 |
| Single click up <sub><sup>(option 1)</sup></sub>     | Up Button                     |
| Single click down <sub><sup>(option 1)</sup></sub>   | Down Button                   |
| Long click up <sub><sup>(option 1)</sup></sub>       | Right Button                  |
| Long click down <sub><sup>(option 1)</sup></sub>     | Left Button                   |
|                                                      |                               |
| Single click select <sub><sup>(option 2)</sup></sub> | Toggle play/pause             |
| Single click up <sub><sup>(option 2)</sup></sub>     | Short Forwords (+30 seconds)  |
| Single click down <sub><sup>(option 2)</sup></sub>   | Short Backwords (-30 seconds) |
| Long click up <sub><sup>(option 2)</sup></sub>       | Long Forwords (+10 minutes)   |
| Long click down <sub><sup>(option 2)</sup></sub>     | Long Backwords (-10 minutes)  |

## VLC

### Features

* Toggle play/pause.
* Increment or decrement volume 5% and set it to lowest or highest.
* Seek +- 10 seconds and +- 1 minute.
* Title text on top displays the filename VLC provides, or an error if one occurs.
* Status gets the status from VLC - should be "Playing", "Paused", "Stopped", or "Unknown" when not known.
* Volume is displayed in a progress bar and as text; both range from 0% to 200% (0% when unknown).
* Seek progress bar shows how far in the movie you are.

### Controls

| Button                                             | Function                  |
| -------------------------------------------------- | ------------------------- |
| Single click select                                | Toggle play/pause         |
| Long click select                                  | Switch between option 1/2 |
|                                                    |                           |
| Single click up <sub><sup>(option 1)</sup></sub>   | Increment volume 5%       |
| Single click down <sub><sup>(option 1)</sup></sub> | Decrement volume 5%       |
| Long click up <sub><sup>(option 1)</sup></sub>     | Set volume to 0%          |
| Long click down <sub><sup>(option 1)</sup></sub>   | Set volume to 200%        |
|                                                    |                           |
| Single click up <sub><sup>(option 2)</sup></sub>   | Seek +10 seconds          |
| Single click down <sub><sup>(option 2)</sup></sub> | Seek -10 seconds          |
| Long click up <sub><sup>(option 2)</sup></sub>     | Seek +1 minute            |
| Long click down <sub><sup>(option 2)</sup></sub>   | Seek -1 minute            |

## XBMC

### Features

* Toggle play/pause.
* Press select, back, up, down, left, and right buttons.
* Increment and decrement volume and set it to lowest or highest.
* Seek short and long.
* Title text on top displays the filename XBMC provides, or an error if one occurs.
* Status displays either "Playing", "Paused", "Stopped", or "Unknown" when not known.
* Volume is displayed in a progress bar and as text; both range from 0% to 100% (0% when unknown).
* Seek progress bar shows how far in the movie you are.

### Controls

| Button                                               | Function                      |
| ---------------------------------------------------- | ----------------------------- |
| Long click select                                    | Switch between options 1/2/3  |
| Double click select                                  | Back Button                   |
|                                                      |                               |
| Single click select <sub><sup>(option 1)</sup></sub> | Select Button                 |
| Single click up <sub><sup>(option 1)</sup></sub>     | Up Button                     |
| Single click down <sub><sup>(option 1)</sup></sub>   | Down Button                   |
| Long click up <sub><sup>(option 1)</sup></sub>       | Left Button                   |
| Long click down <sub><sup>(option 1)</sup></sub>     | Right Button                  |
|                                                      |                               |
| Single click select <sub><sup>(option 2)</sup></sub> | Toggle play/pause             |
| Single click up <sub><sup>(option 2)</sup></sub>     | Short Backwords (-30 seconds) |
| Single click down <sub><sup>(option 2)</sup></sub>   | Short Forwords (+30 seconds)  |
| Long click up <sub><sup>(option 2)</sup></sub>       | Long Backwords (-10 minutes)  |
| Long click down <sub><sup>(option 2)</sup></sub>     | Long Forwords (+10 minutes)   |
|                                                      |                               |
| Single click select <sub><sup>(option 3)</sup></sub> | Toggle play/pause             |
| Single click up <sub><sup>(option 3)</sup></sub>     | Increment volume              |
| Single click down <sub><sup>(option 3)</sup></sub>   | Decrement volume              |
| Long click up <sub><sup>(option 3)</sup></sub>       | Set volume to 100%            |
| Long click down <sub><sup>(option 3)</sup></sub>     | Set volume to 0%              |

## Release Notes

#### v1.0.1

* Fix XBMC authentication issue.

#### v1.0

* Initial release.

## License

Skipstone is available under the MIT license. See the LICENSE file for more info.
