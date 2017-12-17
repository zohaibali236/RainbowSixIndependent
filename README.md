### `Rainbow Six Independent: An external source`

Basic feature list:

* ESP (health bars, names, boxes)
* Aimbot (uses mouse event)
* No recoil and no spread

Note:

```
This will not work with BattlEye running, it either needs a bypass or can only be used if BattlEye is terminated because BE will just strip the handle and you won't be able to get a base address, or read/write memory.
```

Props to Jared and his external source, this is basically just what he released but it actually works (opens a handle and I added a menu and stuff for the different features)

How to compile:

* Download and install the DirectX June 2010 SDK and add the includes and libs (x64) to the project
* Launch Rainbow without BattlEye running (you can do this by terminating BE from task manager after the game is open or you can add the `belaunch -be` parameter to the game in Uplay)
* Compile and run
