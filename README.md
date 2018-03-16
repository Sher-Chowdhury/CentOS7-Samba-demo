### Overview

```

+--------------------------+              +--------------------------+
|                          |              |                          |
|       nfs-storage        |              |        nfs-client        |
|     (IP: 10.0.6.10)      |              |                          |
|                          |              |                          |
|                          |              |                          |
|                          |              |                          |
|                          |              |                          |
|   +-----------------+    |              |     +---------------+    |
|   | /nfs/export_ro  |<----------------------->| /mnt/ref_data |    |
|   +-----------------+    |              |     +---------------+    |
|                          |              |                          |
|   +-----------------+    |              |     +---------------+    |
|   | /nfs/export_rw  |<----------------------->| /mnt/backups  |    |
|   +-----------------+    |              |     +---------------+    |
|                          |              |                          |
|                          |              |                          |
+--------------------------+              +--------------------------+


```