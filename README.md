# kitt

Static site for `https://kitt.techdarkside.com`, served by GitHub Pages.

- `/.well-known/appspecific/com.tesla.3p.public-key.pem`: Tesla Fleet API public key (EC prime256v1). The private key is kept outside this repo.
- `/callback/`: OAuth redirect target. Forwards `?code=…&state=…` to the iOS app at `kitt://callback`.
- `.nojekyll`: stops Jekyll from dropping the `.well-known` directory.
