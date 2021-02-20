- [x] use partialzip instead of downloading the whole IPSW file
- [x] build dependencies into bin/ automatically
- [x] make binary paths dynamic
- [x] make arguments optional
- [x] if device info isn't provided, read DFU device with irecovery
- [x] implement ipsw.me API handler to recognize device and get fw url
- [x] handle deb folder in script directory since it doesn't need to be re-downloaded for other device+version combinations
- [ ] if no shsh2 is provided, get an apticket using tsschecker(if installed) or with shsh.host api
- [ ] download() function for all downloads (handle wget/curl dependencies within it)
- [x] CFPropertyList library to read buildmanifest and properly identify images
- [ ] better logging
- [ ] debian parser to parse repositories and download debs by package identifier and version
- [ ] fix patching A9?