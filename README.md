# DroidBridge Binaries Repository

This repository hosts the pre-built platform-specific binaries for the [DroidBridge](https://github.com/Lusan-sapkota/DroidBridge) extension's smart download system. These binaries enable seamless device interaction by providing required executables like ADB and scrcpy for different operating systems.

## Binary List

The repository includes the following binaries:

- `adb-linux-x64` - Android Debug Bridge binary for Linux (64-bit)
- `adb-macos-x64` - Android Debug Bridge binary for macOS (Intel/x64)
- `adb-windows-x64.exe` - Android Debug Bridge binary for Windows (64-bit)
- `scrcpy-linux-x64` - Scrcpy screen mirroring binary for Linux (64-bit)
- `scrcpy-macos-x64` - Scrcpy binary for macOS (Intel/x64)
- `scrcpy-windows-x64.exe` - Scrcpy binary for Windows (64-bit)

(Additional ARM64 macOS binaries are not added.)

## Usage

These binaries are intended to be downloaded automatically by the DroidBridge extension. Ensure your DroidBridge config points to the correct URL for this repository's releases or file hosting:

github: 'https://github.com/Lusan-sapkota/droidbridge-binaries/releases/latest/download'

## Structure

All binaries are stored in a flat directory structure for ease of access and downloading. Each binary is renamed according to platform and architecture for consistent identification.

## Updating Binaries

To update:

1. Download the latest official platform-tools and scrcpy binaries for all supported platforms.
2. Extract and rename binaries following the naming pattern above.
3. Commit and push changes to this repository.
4. Create a new GitHub release with the updated binaries.

Automate this process when possible using GitHub Actions or other CI tools.

## Security

- All downloads should use HTTPS.
- Verifying checksum integrity of binaries before usage is recommended for enhanced security.

## License

MIT license

## Acknowledgements

This repository hosts platform-specific binaries for the [DroidBridge](https://github.com/Lusan-sapkota/DroidBridge) extension’s smart download system.

The binaries include:

- **ADB (Android Debug Bridge)** from the Android Open Source Project: https://developer.android.com/studio/releases/platform-tools  
- **Scrcpy** screen mirroring tool by Genymobile: https://github.com/Genymobile/scrcpy

The DroidBridge project and this binary repository build upon and redistribute these tools for seamless device integration.

Please refer to the main DroidBridge repository for usage instructions, contribution guidelines, and further details:

https://github.com/Lusan-sapkota/DroidBridge
---

For questions or contributions, please open an issue or pull request on this repository.

