# NetWorth website

The website of the NetWorth app, published with GitHub Pages at
https://alexander7161.github.io/net-worth/

Plain HTML and CSS, no build step:

| Page | File | URL |
|---|---|---|
| Landing page | `index.html` | https://alexander7161.github.io/net-worth/ |
| Support | `support/index.html` | https://alexander7161.github.io/net-worth/support/ |
| Privacy policy | `privacy/index.html` | https://alexander7161.github.io/net-worth/privacy/ |

`assets/style.css` is shared by all pages. The screenshots in `assets/screens/` are the iOS store
listing images (`store/ios-6.9/` in the app repo), resized to 660 px wide JPEGs.

## Privacy policy

The app links to the privacy policy from the Pro screen (`PRIVACY_URL` in
`src/entitlements/products.ts` of the app repo), and it is the Privacy Policy URL in App Store
Connect and Google Play Console. When the app starts sending or storing data differently, update
the page and its effective date.

## App Store link

The App Store button on the landing page says "Coming soon" until the app is live. Replace its
`href` with the App Store URL and remove the `disabled` class.

## Preview locally

```bash
python3 -m http.server 8000
```
