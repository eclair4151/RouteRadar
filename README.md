# Route Radar website

Static marketing, support, and privacy site for Route Radar.

## Deploy to GitHub Pages

1. Create an empty GitHub repository for this directory.
2. Push this directory's contents to the repository's default branch.
3. In **Settings → Pages**, select **Deploy from a branch**, then choose the default branch and the repository root (`/`).
4. In **Settings → Pages**, set the custom domain to `routeradar.app` and enable **Enforce HTTPS** once GitHub makes it available.
5. Configure the DNS records GitHub Pages displays for `routeradar.app`. Add a `www` CNAME only if you also want `www.routeradar.app`.

The root `CNAME` file keeps the custom-domain setting in source control. `.nojekyll` makes GitHub Pages serve all static files as-is.

## Future universal links

When the iOS app is ready to handle universal links, add an `apple-app-site-association` file at `.well-known/apple-app-site-association`. It needs the final Apple Team ID and bundle ID, so it is intentionally not included yet.
# RouteRadar
