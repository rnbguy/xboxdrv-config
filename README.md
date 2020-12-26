# xboxdrv-config
xboxdrv config files

1. Connect your controller and use `evtest` to note the device event number.
2. Run `xboxdrv --evdev <device/event/number> --config <path/to/config/file>`