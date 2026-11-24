# File Browser transfer fixes

This patch set contains the reviewed source changes from the locally tested LC Fix 10 series. It targets upstream [File Browser Quantum](https://github.com/gtsteffaniak/filebrowser) at commit aa4dd3ae95ea8f54959e3df8187b4c02247601cb.

1. Clone the upstream repository and check out the pinned commit.
2. Run git apply --check with the absolute path to filebrowser-transfer-fixes.patch, then run git apply with the same path.
3. Build using the upstream project instructions.

The patch covers transfer reliability and navigation changes. Production configuration, databases, binaries, local browser test harnesses and deployment packaging are stored separately. The upstream Apache-2.0 license is included.
