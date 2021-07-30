# usbip-client

This role could be useful when you need to attach your USB devices on another machine in your network, e.g. a device with radio that needs to be placed in a central place.
Use it in combination with the usbip-server role for the machine that actually has the devices plugged in.

## Example

You can find the bus id with `usbip list -r <usb-server-host>`.

```yaml
usbip_client_devices:
  - host: <usb-server-host>
    bus_id: 1-1.1
```
