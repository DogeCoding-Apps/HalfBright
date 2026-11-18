# HalfBright

> **Note:** This repository hosts official documentation, release notes, privacy policy, and public issue tracking for the Microsoft Store release of **HalfBright**. Source code is maintained in a private repository.

**HalfBright** is a lightweight, native C++/WinRT desktop utility for Windows 10 and Windows 11 that lets you selectively dim bright screen regions—such as game HUDs, static UI toolbars, or blinding white panels—without darkening your entire display.

## Key Features
* **Localized, Feathered Dimming Zones:** Place multiple independent dimming masks anywhere across single or multi-monitor setups with adjustable opacity and smooth edge feathering.
* **HDR-Aware DWM Overlay:** Built directly on the Desktop Window Manager (DWM) to attenuate peak luminance cleanly in both SDR and HDR without washing out colors.
* **Zero-Hook & Anti-Cheat Safe:** Uses passive, click-through overlay windows—never injects DLLs, hooks DirectX/Vulkan APIs, or reads game memory.
* **Native Performance:** Written in modern ISO C++20 and WinUI 3 for minimal CPU, GPU, and RAM overhead.
* **Private & Offline:** Zero telemetry, zero analytics, and zero network connections. All profiles are stored locally on your machine.

## Download
Available on the **Microsoft Store** *(link coming soon)*.

## Support & Issues
Have a bug report, feature request, or multi-monitor edge case? Open an issue in the [Issues](../../issues) tab or reach out to `DogeCoding@outlook.com`.

## Privacy
See [PRIVACY.md](./PRIVACY.md) for our privacy policy.

## Copyright
© 2026 DogeCoding. All rights reserved.
