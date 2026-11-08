# Chris Sommers

Senior Systems & Quality Engineer. 30+ years in software quality, consumer device platforms (OOBE/NUX), and test infrastructure, including 18 years at Apple.

## Projects

- [cable-uhid-bridge](https://github.com/baseman70/cable-uhid-bridge): Linux user-space daemon (Rust) that emulates a USB FIDO2 security key over `/dev/uhid` and tunnels WebAuthn requests to iOS and Android passkeys via FIDO Hybrid Transport (caBLE v2).
- [LinkMyStreamer](https://github.com/baseman70/linkmystreamer-showcase) ([linkmystreamer.com](https://www.linkmystreamer.com)): Cross-platform music link resolver (React Native, Expo, TypeScript) that routes shared tracks directly into native streaming apps via iOS Universal Links and Android App Links.
- `lab-ctl`: Agentless SSH fleet management, security auditing, and DNS/network automation CLI for a mixed Linux (Arch, Ubuntu, Debian/Raspberry Pi) and macOS (Apple Silicon) lab.

## Upstream Contributions

- Linux Kernel (`drivers/input/serio/i8042`): Added `SERIO_QUIRK_RESET_ALWAYS` DMI quirk (`25e424eb4ae1`) to fix keyboard controller dropouts on Acer Aspire Go 15 (`AG15-42P`) laptops.
- Canonical `snapd` ([PR #17727](https://github.com/canonical/snapd/pull/17727)): Updated the `u2f-devices` AppArmor interface to permit virtual `/dev/uhid` HID report descriptors in confined browsers.
- Pi-hole ([PR #6698](https://github.com/pi-hole/pi-hole/pull/6698)): Fixed quiet-mode flag propagation and logrotate output handling in `piholeLogFlush`.
- Omarchy (`omacom/omarchy`): Bug fixes and hardware workarounds for Wayland lock-screen IPC timeouts ([PR #15877](https://github.com/omacom/omarchy/pull/15877)), clipboard image pasting ([PR #10536](https://github.com/omacom/omarchy/pull/10536)), laptop clickpad selection behavior in `foot` ([PR #18068](https://github.com/omacom/omarchy/pull/18068)), and boot configuration ([PR #10519](https://github.com/omacom/omarchy/pull/10519)).

## Contact

- LinkedIn: [linkedin.com/in/chrissommersqa](https://www.linkedin.com/in/chrissommersqa/)
- Email: [chris.sommers@icloud.com](mailto:chris.sommers@icloud.com)
