# Focused Lens — Releases

Public distribution point for **Focused Lens** desktop app binaries (macOS `.dmg`, Windows `.exe`).

The application source lives in the private `spaggle/focused-lens` repository. Because that
repo is private, its release assets cannot be downloaded anonymously — so published binaries
are mirrored here, where the download page and any visitor can fetch them without
authentication.

## Downloads

Get the latest build from the [Releases](https://github.com/spaggle/focused-lens-releases/releases)
page, or from the app's download page.

Each release lists the version, publish date, and SHA-256 checksum. **Verify the checksum before
installing** — `shasum -a 256 <file>` on macOS, `Get-FileHash <file>` on Windows.

## Notes

- macOS builds are currently **unsigned and Apple Silicon only**. macOS blocks the first launch;
  open via System Settings → Privacy & Security → Open Anyway.
- Releases here are published automatically by CI in the source repository.
