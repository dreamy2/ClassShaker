# ClassShaker

First of all, I would like to 100% credit Sleitnick, the original creator of [RbxCameraShaker.](https://github.com/Sleitnick/RbxCameraShaker/tree/master)

The module can be grabbed from [this model.](https://create.roblox.com/store/asset/18112491559/ClassShaker)

## Instructions
You can download **TestPlace.rbxl** to view quick examples of how to use.
This module only works for **Models, Attachments, BaseParts, Cameras, NumberValues and GuiObjects.**

## ClassShaker.new():

| Argument | Description |
| ------ | ----------- |
| `Argument 1` | Object you want to affect. |
| `Argument 2` | Settings table. |

**Settings**

It should be noted that settings are not required to be passed, the module will just use its defaults.

| Setting | Description |
| ------ | ----------- |
| `PositionSensitivity` | Increase or decrease the position shake. (Default: 1) |
| `RotationSensitivity` | Increase or decrease the rotation shake. (Default: 1) |
| `OffsetRotation` | Primarily used for GuiObjects. Example: If my GUI is upside down, this should be 180. (Default: 0) |
| `RenderPriority` | RenderPriority, self explanatory (Default: Enum.RenderPriority.Camera.Value) |
| `UpdateHz` | The update hz of the shake. (Default: Player's Framerate) |

**Items Returned**

| Item | Description |
| ------ | ----------- |
| `Shaker Library` | Library for shaking your object. (For example, :Shake(), :ShakeOnce(), :Stop(), and more.) |
| `Shaker Presets` | Presets that can be used for your object's shake. |

**Presets**
```
Bump, Bump2, Explosion, Earthquake, BadTrip, HandheldCamera, Vibration, RoughDriving
```

## End

That is all currently for this module. There are extra features from [RbxCameraShaker](https://github.com/Sleitnick/RbxCameraShaker/tree/master) that can be used here, feel free to check it out!

Join my [discord server](https://discord.gg/2JdU9x4usT) if you run into any problems, or if you would like to ask anything.
