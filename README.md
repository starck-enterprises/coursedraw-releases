# CourseDraw releases

Public download artifacts for the CourseDraw desktop app (macOS and Windows).

- **Source code:** private — [`starck-enterprises/coursedraw`](https://github.com/starck-enterprises/coursedraw)
- **Binaries:** GitHub Releases on this repository (open for download without GitHub login)

## Latest beta

See [Releases](https://github.com/starck-enterprises/coursedraw-releases/releases).

Example download URLs (set as `BETA_DOWNLOAD_URL_MACOS` / `BETA_DOWNLOAD_URL_WINDOWS` on the API):

```text
https://github.com/starck-enterprises/coursedraw-releases/releases/download/v0.1.0-beta.11/CourseDraw_0.1.0-beta.11_aarch64.dmg
https://github.com/starck-enterprises/coursedraw-releases/releases/download/v0.1.0-beta.11/CourseDraw_0.1.0-beta.11_x64-setup.exe
```

## Notes

- Builds are invite-only for access; the download links themselves are public.
- **macOS:** Apps may be ad-hoc signed (not Apple-notarized). If macOS says the app is damaged:

```bash
xattr -cr /Applications/CourseDraw.app
```

- **Windows:** The NSIS installer is unsigned. If SmartScreen appears, choose **More info** → **Run anyway**.
