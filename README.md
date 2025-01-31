# verify-medium-integrity

This script can be used to detect if an installation medium of RPM-based Linux distribution (OpenMandriva, openSUSE, Fedora, etc.) is corrupted. It does so by comparing files on the disk to metadata in RPM database.

See `VERIFY OPTIONS` section of `man 8 rpm` for the detailed explanation of the output.

## Usage

While booted from your installation media, run:

```
wget https://raw.githubusercontent.com/cryptopotatus/verify-medium-integrity/refs/heads/main/verify-medium-integrity
chmod +x verify-medium-integrity
sudo ./verify-medium-integrity
```

