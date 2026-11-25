> **Windows 下载**　[LC Fix 10 Release](https://github.com/136084599/filebrowser-transfer-fixes/releases/tag/v2.0.1-lcfix10)提供已构建的服务 EXE、整包、示例配置和校验值。直接使用 Windows 整包时无需下载上游。下方的上游提交只用于自行应用补丁和复现构建。
> 修复源码在 [`lcfix10` 分支](https://github.com/136084599/filebrowser/tree/lcfix10)。[下载、首次启动、升级、回滚和构建说明](https://github.com/136084599/filebrowser/blob/lcfix10/LCFIX10.md)。
> 本仓保存可应用到指定上游提交的补丁和许可证，便于查看修改与复现。上游为 [File Browser Quantum](https://github.com/gtsteffaniak/filebrowser)。

# File Browser transfer fixes

This patch set contains the reviewed source changes from the locally tested LC Fix 10 series. It targets upstream [File Browser Quantum](https://github.com/gtsteffaniak/filebrowser) at commit aa4dd3ae95ea8f54959e3df8187b4c02247601cb.

1. Clone the upstream repository and check out the pinned commit.
2. Run git apply --check with the absolute path to filebrowser-transfer-fixes.patch, then run git apply with the same path.
3. Build using the upstream project instructions.

The patch covers transfer reliability and navigation changes. Prebuilt Windows files are available in the Release linked above. Production configuration, databases, and local test harnesses stay with their deployment. The upstream Apache-2.0 license is included.
