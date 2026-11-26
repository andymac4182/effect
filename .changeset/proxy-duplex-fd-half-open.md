---
"@effect/platform-node-shared": patch
---

Fix `NodeChildProcessSpawner.layerProxyProcess` losing writes and write errors on duplex file descriptors when the child closes the descriptor immediately after starting.
