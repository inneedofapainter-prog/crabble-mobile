# Crash hotfix

This package rolls back the unstable multi-select update and restores the latest stable Stats/Profile/Lobby/Word Policy build.

It also adds stronger no-cache headers and a new web bundle filename so mobile browsers fetch the corrected app after deployment.

Deploy by copying these files to the GitHub repo root, overwriting existing files, then redeploying Render with a clear build cache.
