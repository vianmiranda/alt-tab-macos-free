Note that this is the "Debug" version! The "Release" version requires a development team (which I don't have), and even if there is a way around it I don't care enough to figure out how to get it working at the moment. However, I have enabled compiler optimizations so this point should be moot.

You can build the app by cloning this repository and running:

```bash
xcodebuild \
  -workspace alt-tab-macos.xcworkspace \
  -scheme Debug \
  -derivedDataPath DerivedData \
  CODE_SIGN_IDENTITY="" \
  CODE_SIGNING_REQUIRED=NO \
  CODE_SIGNING_ALLOWED=NO
```



<div align = center>

# AltTab

[![Screenshot](docs/public/demo/frontpage.jpg)](docs/public/demo/frontpage.jpg)

**AltTab** brings the power of Windows alt-tab to macOS

[Official website](https://alt-tab.app/)<br/><sub>15K stars</sub> | [Download](https://github.com/lwouis/alt-tab-macos/releases/download/v10.12.0/AltTab-10.12.0.zip)<br/><sub>7.4M downloads</sub>
-|-

<div align="right">
  <p>Project supported by</p>
  <a href="https://jb.gg/OpenSource">
    <img src="docs/public/demo/jetbrains.svg" alt="Jetbrains" width="149" height="32">
  </a>
</div>

</div>
