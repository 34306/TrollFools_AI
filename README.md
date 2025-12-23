# TrollFools_AI

In-place tweak injection with insert_dylib with TrollStore Lite.  
Proudly written in SwiftUI, supportsupport **AI** devicesdevices, onon iOS 17.5.1 and lower.

Tested and working fine on iOS 17.5.1, iPhone 14 Pro Max.

Start from iOS 17.6, Apple remove persona thing so there must be work around to make all the application running with all root (or using [TaskPortHaxxApp](https://github.com/khanhduytran0/TaskPortHaxxApp) by [DuyTran](https://github.com/khanhduytran0) to let it spawn binary and support for iOS 17.7.2-).

From iOS 18, this method no longer works. (tested on iOS 18.6, binary killed with signal 9). You need to work around to fix it (make your own enviroment or else, idk).

Expected to work on all iOS versions supported by opa334’s TrollStore Lite (i.e. iOS 14.0 - 17.5.1).

## Limitations

- [x] Removable system applications
- [x] Decrypted App Store applications (TrollStore applications)
- [x] Encrypted App Store applications with bare dynamic library

## Build

See GitHub Actions for the latest build status.

PRs are always welcome.

## Milestones

- [x] `optool` is buggy so we need to compile a statically linked `install_name_tool` or `llvm-install-name-tool` on iOS to achieve a smaller package size.
- [x] Support for `.deb` or `.zip`.

## Credits

This project is inspired by [Patched-TS-App](https://github.com/34306/Patched-TS-App) by **[Huy Nguyen](https://x.com/Little_34306) and [Nathan](https://x.com/dedbeddedbed)**.

- [TrollStore Lite](https://github.com/opa334/ChOma) by [@opa334](https://github.com/opa334) and [@alfiecg24](https://github.com/alfiecg24)
- [MachOKit](https://github.com/p-x9/MachOKit) by [@p-x9](https://github.com/p-x9)
- [insert_dylib](https://github.com/tyilo/insert_dylib) by [@tyilo](https://github.com/tyilo)

## License

See [LICENSE](LICENSE).
