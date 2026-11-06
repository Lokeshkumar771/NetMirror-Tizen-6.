# NetMirror for TizenBrew

A minimal TizenBrew application module that launches the NetMirror web address
`https://net77.cc/home`.

## Files

- `package.json` — TizenBrew app-module metadata.
- `app/index.html` — simple TV-friendly launcher that redirects to NetMirror.

## Install through TizenBrew

1. Push this folder to a GitHub repository.
2. In TizenBrew Installer, choose the GitHub repository install option.
3. Enter the repository as `YOUR_GITHUB_USERNAME/NetMirror-Tizen`.
4. Install the module on the Samsung TV.

## Notes

- This is a launcher, not a copy of the NetMirror website or its video content.
- It does not bypass subscriptions, paywalls, DRM, or access restrictions.
- The target website must remain reachable and compatible with the TV's browser.
- If the target website blocks the TV browser or its video codecs, the launcher
  cannot fix that by itself.
