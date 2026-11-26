---
"@effect/platform-node-shared": patch
---

Fix `NodeChildProcessSpawner.layerProxyProcess` losing duplex file descriptor half-open mode and write errors when the child closes the fd before `Spawned` is received.
