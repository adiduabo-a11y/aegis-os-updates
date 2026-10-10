# AEGIS signed updates

Public downloads for AEGIS desktop releases and OS updates. Bundles contain verified application code, native tools and operating system updates. They contain no user data, models, private keys or credentials.

## Update channels

- **Desktop updates (Schema 1):** `manifest.json`, `manifest.sig`, `payload.tar.gz`. Managed via Aegis Updates in user space; updates desktop shell, widgets and allowlisted native helpers.
- **System updates (Schema 2):** `os-manifest.json`, `os-manifest.sig`, `os-payload.tar.gz`. Administrator-authenticated via `aegis-os-update`; updates system services, firewall, local search, Python environments and signed APT packages (kernels, firmware, drivers).
- **Bootable live media:** Surface Pro 7 and amd64 ISO images and `SHA256SUMS`.

Publisher public-key SHA256 (DER): `3235a10f1ea6f4ac52f443738c7ab3500d9e22601260ccc2103f9927f85a9b0b`.
Trust is provisioned in the image; a key downloaded beside a bundle does not establish trust.
