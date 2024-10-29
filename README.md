# homepage
Website made in Angular


# To update the website and Redeploy

1. `ng build --output-path=docs --base-href "https://emzedi.github.io/homepage/"`
2.  `npx angular-cli-ghpages --dir=docs/browser`
3. `mv docs/browser/* docs/`
4. go to `docs/main-2TY5DXLB.js` and replace `../../assets` with `./assets` everywhere.

And finally commit and push to the main branch.
