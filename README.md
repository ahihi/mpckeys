# mpckeys

Scripts and configuration to control MPD using the media keys on Apple keyboards.

## Requirements

- Mac OS X
- [MPD](http://mpd.wikia.com/)
- [MPC](http://mpd.wikia.com/wiki/Client:Mpc)
- [Karabiner](https://pqrs.org/osx/karabiner/) (formerly KeyRemap4Macbook)

## Usage

1. Put the `.app`s and `mpckeys-remap.xml` into `/Applications/MPCKeys/`. (symlinks work too)
2. In the "Misc & Uninstall" tab of Karabiner, click Custom Setting → Open private.xml, and open the file in a text editor.
3. Add the line `<include path="/Applications/MPCKeys/mpckeys-remap.xml" />` inside the `<root>` node of the configuration and save it.
4. In the "Change Key" tab of Karabiner, click ReloadXML.
5. A checkbox labeled "MPCKeys" appears in the remapping list. Make sure it's checked.
6. Now your "play/pause", "previous track" and "next track" keys control MPD!