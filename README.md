# GodotVR

Experimental, lightweight VR social platform in Godot.

First things to implement:
- tracking
- teleportation movement

## Roadmap

- Physbones (has a default angle but will flop with movement)
- Rigbones (tracks your movement)
- [Multiplayer](https://docs.godotengine.org/en/stable/tutorials/networking/high_level_multiplayer.html) (serialization ;-;)
- Modding support (custom worlds/models)
  - Mods must be structured `res://mods/<YOUR MOD NAME>/<CONTENT>` and saved as `<YOUR MOD NAME>.pck`.
  - A [FileDialogue](https://docs.godotengine.org/en/stable/classes/class_filedialog.html) is used to select your pack file, which is then loaded as a [pack](https://docs.godotengine.org/en/3.2/getting_started/workflow/export/exporting_pcks.html). Assuming it's a valid pack, the pack file is saved to an internal directory so you don't have to reselect it next time.
