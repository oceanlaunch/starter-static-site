# Static website starter

A one-page website in plain HTML and CSS, ready to deploy on [OceanLaunch](https://oceanlaunch.cloud). There is
no build step: OceanLaunch serves the files in this repository with nginx.

- `index.html`: the page
- `styles.css`: its styles (light and dark mode)

Add pages as more `.html` files and link them, for example `about.html` at `/about.html`.

## Deploy it

In the OceanLaunch portal, open **Templates** and choose **Static website**. Your site is live at its
`*.apps.oceanlaunch.cloud` address within a minute or two.

## Make it yours

1. On GitHub, choose **Use this template** to get your own copy of this repository.
2. In the portal, open your app, and under **Make it yours** give your new repository's address.
3. Change the files and push: every push to `main` deploys a new version.

## Preview it on your computer

Open `index.html` in a browser, or serve the folder, for example with `npx serve .`.
