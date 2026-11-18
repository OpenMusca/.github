# OpenMusca

**Open-source, local-only firmware for the PETKIT YumShare Dual-Hopper 2 (P592) pet feeder.**
Control it from Home Assistant over MQTT, without the vendor cloud, with a way back to stock at every step.

> **Experimental, work in progress.** This is unofficial software for hardware that dispenses food for animals.
> It can brick the device, void the warranty, or leave a pet without food. Keep the feeder's own schedule or a
> manual fallback in place and never run it on a device you cannot recover. Use at your own risk.

## Status

Early. A reversible soft-install runs on one P592; own U-Boot and kernel work is in progress; signed updates and
the camera are planned. Expect breaking changes.

## Links

- Website and documentation: https://openmusca.github.io
- Source: [OpenMusca/musca](https://github.com/OpenMusca/musca) (**release coming soon**)
- Website source: [OpenMusca/openmusca.github.io](https://github.com/OpenMusca/openmusca.github.io)
- Security reports: see our [security policy](https://github.com/OpenMusca/.github/blob/main/SECURITY.md)

## Principles

- Local first: no cloud, no telemetry, no analytics.
- Reversible: every step documents the way back to stock.
- Clean room: no vendor firmware, code or images in this organisation; device-specific files come from your own device.
- Safety first: feed limits are enforced in software, feeding is off by default.

## How it is made

Developed with AI coding assistants under human direction, review and hardware testing, with a documented
clean-room process. Details: https://openmusca.github.io/disclaimer/#how-this-project-is-made-ai-assistance

## Disclaimer

OpenMusca is an independent community project. It is not affiliated with, authorised or endorsed by PETKIT.
"PETKIT" and "YumShare" are trademarks of their owners and are used only to name the compatible hardware.
Everything here is provided as is and used **at your own risk**. Full disclaimer, including the legal background for
device owners in Germany and the EU (§ 903 BGB, §§ 69d, 69e UrhG, § 3 GeschGehG): https://openmusca.github.io/disclaimer/
