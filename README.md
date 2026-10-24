# BrewGo version file

The BrewGo mobile app reads `version.json` from this repo at every launch:

https://raw.githubusercontent.com/360ITHUBPVTLTD/brewgo-versions/refs/heads/main/version.json

- `force_update_below`: an installed version lower than this gets an update dialog that cannot be closed, sending
  the user to `store_url`. Raise it only when everyone must move to a new version.
- Keep the repo public: the app downloads the file without logging in.
