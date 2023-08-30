# IMU-Blender-Rigged-Hand

IMU => PySerial => Blender Game Engine => Virtual Hand Control

Blender
-------

- Install blender 2.78:\
https://download.blender.org/release/Blender2.78/

- Install pip inside blender and pyserial:
```
/opt/blender-2.78/2.78/python/bin/python3.5m -m ensurepip --upgrade
/opt/blender-2.78/2.78/python/bin/python3.5m -m pip install pyserial
```

- Open the .blend file with Blender, it will have a python script which will read the values received on the serial port.

- Click on the hand and press "P" to start the animation.

- Press ESC to stop it

