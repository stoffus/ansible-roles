# usbip-client

This role could be useful when you need to attach your USB devices on another machine in your network, e.g. a device with radio that needs to be placed in a central place.
Use it in combination with the usbip-server role for the machine that actually has the devices plugged in.

## Example

This role expects the devices to be exported to be put in a devices variable, see `defaults/main.yml`.
You can find the bus id with `usbip list -r <host>`.
