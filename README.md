# Nova Music

Upload this whole folder to a GitHub repo, then **Settings → Pages → Deploy from branch → main / (root)**.
Share the Pages link: phones get the Android APK, Macs get the Mac download, everyone else opens the web app (`/app`).

- `downloads/Nova-Music.apk` – Android app
- `downloads/Nova-Music-Mac.zip` – Mac app. GitHub Action *Build DMG* turns it into `Nova-Music.dmg` automatically (Actions tab → Build DMG → Run workflow); the page then serves the DMG.
- `app/` – web version (also installable as PWA)

Login page: log in as admin → Admin → *Logo & name* and *Login page* (logo, tagline, colour).
Admin: `admin@gmail.com`, first password `admin` — change it.
