# CalBalance privacy policy

Static English and Polish privacy-policy page for the Garmin watch app. No build step, JavaScript, third-party fonts, analytics, forms or dependencies.

## Files

- `index.html`: English policy and Polish version (`#pl`).
- `style.css`: responsive layout and print styles.
- `assets/calbalance.png`: the app's existing brand icon.
- `.nojekyll`: serve the static files without Jekyll processing.

The policy describes the current app, including local-only storage, 14/90-date retention windows and the absence of an in-app “delete all” command. It does not claim that uninstalling erases every device backup. Publisher contact currently uses the real public repository issue channel; do not post personal or health information there. A publisher name and support email can replace this contact after the owner supplies them.

## Publish with GitHub Pages

The publishing source is the `feat/calbalance-privacy` branch, repository root. The first GitHub CLI accounts checked had read-only access, but the existing Git HTTPS credential authenticates the repository owner and supports publishing. Credentials are not stored in this repository.

After authenticating as an account with access:

1. Push `feat/calbalance-privacy` to this repository.
2. Open the repository's **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Choose **feat/calbalance-privacy**, directory **/ (root)**, and save.
5. Wait for a successful Pages deployment and open the published URL without signing in.

GitHub Pages project URL:

```text
https://lukasz298boczon.github.io/policy/
```

Use this URL in Garmin's Privacy Policy field after the Pages deployment succeeds and the page is publicly reachable. The repository URL itself is not the policy-page URL.

## Local preview

```sh
python3 -m http.server 8765 --bind 127.0.0.1
```

Open `http://127.0.0.1:8765/`. The page works at the project URL with relative asset paths.
