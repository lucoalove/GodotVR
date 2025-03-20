# GodotVR

Experimental, lightweight VR social platform in Godot.

First things to implement:
- tracking
- teleportation movement

## Roadmap

- Physbones (has a default angle but will flop with movement)
- Rigbones (tracks your movement)
- [Multiplayer](https://docs.godotengine.org/en/stable/tutorials/networking/high_level_multiplayer.html) (serialization ;-;)
- Modding support
  - Custom worlds/avatars via Godot [resource packs](https://docs.godotengine.org/en/3.2/getting_started/workflow/export/exporting_pcks.html)
  - Mods must be structured `res://mods/<YOUR MOD NAME>/<CONTENT>` and saved as `<YOUR MOD NAME>.pck` to be loaded properly.
  - Within a (Desktop only?) mod-manager menu, a [FileDialogue](https://docs.godotengine.org/en/stable/classes/class_filedialog.html) is used to select your pack file, which is then saved to an internal directory (so you don't have to reselect the mod; it will automatically appear in the mod-manager menu).
