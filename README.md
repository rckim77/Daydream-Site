# Daydream website

The GitHub Pages website and privacy policy for **Daydream: Explore Cities**.

- Website: https://rckim77.github.io/Daydream-Site/
- App Store: https://apps.apple.com/app/id1366747814
- Contact: daydreamiosapp@gmail.com

## Editing

The privacy policy is in `index.md`. The shared page layout is in `_layouts/default.html`, with styles in `assets/styles.css`. `assets/daydream-icon.png` is the official app icon copied from the Daydream iOS app.

GitHub Pages builds the site with Jekyll from the root of `master`. The existing public URL remains the privacy-policy URL used in App Store Connect. Changes on a pull request do not publish until merged.

For a local preview with Jekyll installed:

```sh
jekyll serve --host 127.0.0.1 --port 4081
```

Open http://127.0.0.1:4081/Daydream-Site/.

When the app’s behavior or SDKs change, review the policy against the app and the SDK privacy manifests before updating it. The data table describes the SDK declarations; it does not replace reviewing optional features such as current-location requests.
