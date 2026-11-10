# Roadmap

## Next engineering patch (after stress testing)

- Prevent CSV exports or non-scan files from appearing as usable entries in scan selection.
- Improve Windows taskbar icon sharpness and scaling while preserving the same matchbox artwork used in the title bar and application.
- Complete real-Windows regression testing of custom dropdowns, DPI, icons, restore, and Recycle Bin behavior.
- Test scan recovery and backup restore under simulated interruptions and large libraries.

## Release readiness

- Build and smoke-test an unsigned Windows executable from the **private** repository.
- Add automated Windows packaging checks, then evaluate code signing and an installer.
- Establish reproducible build versions and documentation for FFmpeg installation.
- Validate on large network shares and live-file-change scenarios before production deployment.

## Potential commercial features

- Personal vs commercial licensing, a reviewed EULA and privacy policy.
- Optional email registration and clearly separated consent for marketing.
- Enterprise deployment, support and centralized license management, only after core safety/UX are stable.
