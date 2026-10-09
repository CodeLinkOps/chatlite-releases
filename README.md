# chatlite-releases

聊轻（chatlite）Android 安装包的公开分发仓库。**这里只有安装包，没有源码。**

- 每个版本一个 Release，tag 形如 `app-test-v0.2.0-b2000900`（`test` / `prod` 是环境，`v` 后是版本号，`b` 后是 Android versionCode）。
- 附件 `chatlite-<版本>-b<build>-arm64.apk`，仅 arm64-v8a。
- App 内「检查更新」拉取的就是这里的附件；安装前会核对 sha256 与大小，覆盖安装依赖 Android 的签名一致性校验。
- 不接受 issue / PR。
