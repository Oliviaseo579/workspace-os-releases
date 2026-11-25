# Workspace OS releases

This public repository hosts **release artifacts only** for Workspace OS and the
Student Edition:

- `latest.yml`
- `Workspace-OS-<version>-Setup.exe`
- `Workspace-OS-<version>-Setup.exe.blockmap`

There is no source code here. Source code lives in the private repositories
`Oliviaseo579/workspace-os` and `Oliviaseo579/workspace-os-student-edition`.

The installed app checks the latest release on this repository (8 seconds after
launch, then every 2 hours). Keeping this repository public means no update token
is embedded in the client and students can download the installer without a
GitHub account.

**No automatic pushes or releases.** See
`docs/GITHUB_PUSH_POLICY.md` in the private source repositories.
