# 3.0.2.6

- Reworked update process with error handling
- Updated & fixed Inno installer script

---

# 3.0.2.5

- Added the ability to move the status widget at the top edge of the screen (if the widget is enabled)

---

# 3.0.2.4

- Fixed a rare bug causing a crash due to a race condition
- Removed some information from the Sentry debug info because of security reasons
- Added repeated automatic update checks after startup (customizable, on every hour by default)

---

# 3.0.2.3

- Added debug information to Sentry calls

---

# 3.0.2.2

- Added the ability to choose the storage mode of the installation GUID
    - Registry (LOCAL MACHINE)
    - Registry (CURRENT USER)
    - Filesystem (guid.txt)
- Reverted the process initialization for the CliniView application handler

---

# 3.0.2.1

- Fixed Folder Watcher widget status label overflow
- The main window only gets focus when it is visible

---

# v3.0.2.0

- Fixed EzDent application errors
- Fixed the API debug options
- Added a way to start the XRay applications synchronously
- Added the ability to DISABLE the automatic startup updates
- Simplified process handling
- Added patient Folder Watcher widget (disabled by default)
- Added Sentry integration

---

# v3.0.1.0

- Removed Conexio support
- Added Owandy Olink support
- Added NNT support

---

# v3.0.0.0

- Initial release [BETA]
