# ClassShaker

First of all, I would like to 100% credit Sleitnick, the original creator of [RbxCameraShaker.](https://github.com/Sleitnick/RbxCameraShaker/tree/master)
The module can be grabbed from [this model.](https://create.roblox.com/store/asset/78454246632452/ClassShaker)

## Why use ClassShaker?
ClassShaker is a simpler version of CameraShaker to use! You can use it on many things, not just the camera. It also contains some optimization methods that default CameraShaker does not have. All you need to do is .new, and your library is ready for use.

## Instructions
You can download **TestPlace.rbxl** to view quick examples of how to use.
This module only works for **Models, Attachments, BaseParts, Cameras, NumberValues, properties with a "number" or "Vector3" type, and GuiObjects.**

## ClassShaker.new():

| Argument | Description |
| ------ | ----------- |
| `Argument 1` | Object you want to shake. |
| `Argument 2` | Settings table. More information below. |

**Settings**

It should be noted that settings are not required to be passed, the module will just use its defaults.

| Setting | Description |
| ------ | ----------- |
| `renderPriority` | RenderPriority, self explanatory (Default: Enum.RenderPriority.Camera.Value + 1) |
| `property` | If you'd like to "shake" a specific property of a part, put the name of the property here. |

Please keep in mind that only Vector3 and number properties are accepted as of v2.

**Items Returned**

| Item | Description |
| ------ | ----------- |
| `Shaker Library` | Library for shaking your object. (Contains: :Shake(), :ShakeOnce(), :Stop(), and more.) |

If you would like to asset presets, use .Presets in the library.

**Presets**
```
Bump, Bump2, Explosion, Earthquake, BadTrip, HandheldCamera, Vibration, RoughDriving
```

## End

That is all currently for this module. There are extra functions carried over from [RbxCameraShaker](https://github.com/Sleitnick/RbxCameraShaker/tree/master) that can be used here, feel free to check it out!

Join my [discord server](https://discord.gg/2JdU9x4usT) if you run into any problems, suggestions, or if you would like to ask anything.
