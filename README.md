# macOS Media Log Stream

A wrapper over the `/usr/bin/log` binary to aid in monitoring application use of the Camera, Microphone, Screen Capture and Location services.

---

* `zig run ./src/main.zig <ignoredService> <ignoredService>`
  * e.g. `./app "loc:System Services" screen:com.lwouis.alt-tab-macos`
* `zig build`

---

This app ignores `loc:System Services` and `screen:com.lwouis.alt-tab-macos` events
