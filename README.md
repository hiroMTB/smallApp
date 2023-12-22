# small macOS C++ proejct for build, codesign and release with Github Actions
The project only needs less than a minute to checkout, compile, and codesign for shortest execution time.
Tested with self-signed certificate made on my macOS, without developer program.

## Memo
- Apple's Official article for certificate and codesign
https://docs.github.com/en/actions/deployment/deploying-xcode-applications/installing-an-apple-certificate-on-macos-runners-for-xcode-development

- Useful info by Jan Bílek
https://localazy.com/blog/how-to-automatically-sign-macos-apps-using-github-actions

- How to solve permission denied issue (after download app and open app)
https://github.com/marketplace/actions/upload-a-build-artifact#permission-loss
