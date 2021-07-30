# usbip-server

This role could be useful when you need to attach your USB devices on another machine in your network, e.g. a device with radio that needs to be placed in a central place.
Use it in combination with the usbip-client role for the consuming machine.

## Example

You can find the bus id with `usbip list -l`.

```yaml
usbip_server_devices:
  - 1-1.1 # i.e. bus id
```
