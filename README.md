# fritzanity.github.io

Static GitHub Pages site whose sole purpose is hosting the Tesla Fleet API
third-party public key at:

`/.well-known/appspecific/com.tesla.3p.public-key.pem`

The file contains only a public key. The matching private key lives in the
macOS Keychain and is never committed. `.nojekyll` is required so Pages
serves the dot-directory.
