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

Refer to [docs.clearpathrobotics.com](https://docs.clearpathrobotics.com/docs_robots/outdoor_robots/husky/a200/maintenance_husky#maintenance_husky_motor_controller_firmware) for installation instructions.

| Robot     | Description                                                                             | File Name                                   | Last Updated | Update Notes |
| :-------- | :-------------------------------------------------------------------------------------- | :------------------------------------------ | :----------- | :----------- |
| Dingo     | Standard Dingo-Differential and Dingo-Omnidirectional firmware for Puma II (backwards compatibly with with Puma)| motor_controller_firmware_dingo_003.bin     |              |              |
| Husky     | Allows the Husky to roll during `/cmd_vel` with zero velocity.                          | motor_controller_firmware_husky_001.bin     | 2026/04/15 | Fixed bug in encoder reporting |
| Husky     | Resists rolling by applying electrical power to the motors when `/cmd_vel` is set to zero. | motor_controller_firmware_husky_002.bin     |              |              |
| Ridgeback | Standard Ridgeback firmware.                                                            | motor_controller_firmware_ridgeback_001.bin |              |              |
