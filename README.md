# CourseDraw releases

Public download artifacts for the CourseDraw macOS app.

- **Source code:** private — [`starck-enterprises/coursedraw`](https://github.com/starck-enterprises/coursedraw)
- **Binaries:** GitHub Releases on this repository (open for download without GitHub login)

## Latest beta

See [Releases](https://github.com/starck-enterprises/coursedraw-releases/releases).

Example download URL (set as `BETA_DOWNLOAD_URL` on the API):

```text
https://github.com/starck-enterprises/coursedraw-releases/releases/download/v0.1.0-beta.3/CourseDraw_0.1.0-beta.3_aarch64.dmg
```

## Notes

- Builds are invite-only for access; the download link itself is public.
- Apps may be ad-hoc signed (not Apple-notarized). If macOS says the app is damaged:

```bash
xattr -cr /Applications/CourseDraw.app
```
