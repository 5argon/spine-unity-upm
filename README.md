# spine-unity-upm

This is a [Unity Package Manager](https://docs.unity3d.com/Packages/com.unity.package-manager-ui@latest/) compatible version of [Esoteric Software's Spine](http://esotericsoftware.com/) Unity runtime based on a .unitypackage obtained from [this page](http://esotericsoftware.com/spine-unity).

In your `manifest.json`, add this line to pull into your project.

```
    "com.esotericsoftware.spine": "git://github.com/5argon/spine-unity-upm.git",
```

To update, delete the `lock` section appeared at bottom of the `manifest.json`.