# Security Policy

## Reporting a Vulnerability

For any abuse reports or security concerns, please open an issue in this repository.

We take all reports seriously and will respond within 48 hours.

## Scope

This tool works with local build and loadout data. It does not:

- Inject DLLs into game processes
- Modify game memory
- Alter game installation or save files
- Access network resources
- Collect telemetry

The build library is stored locally next to the executable, and a timestamped backup is written before every save. If you believe a release behaves differently, open an issue with the version number and the steps that produced it.