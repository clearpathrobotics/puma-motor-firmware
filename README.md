# puma-motor-firmware

This repository stores public facing binary files and tools for changing the firmware on Clearpath Robotics _Puma Motor Controllers_.
These binary files are copies from an internal Clearpath Robotics repository.

_Puma Motor Controllers_ are used on [Husky](https://clearpathrobotics.com/husky-unmanned-ground-vehicle-robot/), [Dingo](https://clearpathrobotics.com/dingo-indoor-mobile-robot/), and [Ridgeback](https://clearpathrobotics.com/ridgeback-indoor-robot-platform/).

<center>
  <img
    src="/readme_image_puma.png"
    width="600"
  />
</center>

---

Refer to [docs.clearpathrobotics.com](https://docs.clearpathrobotics.com/robots/husky/maintenance_husky#maintenance_husky_motor_controller_firmware) for installation instructions. 

| Robot | Description                                                                             | File Name                               |
| :---- | :-------------------------------------------------------------------------------------- | :-------------------------------------- |
| Husky | Allows the Husky to roll during `/cmd_vel` with zero velocity.                          | motor_controller_firmware_husky_001.bin | 
| Husky | Resists rolling by appling electral power to the motors when `/cmd_vel` is set to zero. | motor_controller_firmware_husky_002.bin |
