---
"@ai-hero/sandcastle": patch
---

Add opt-in dependency-path isolation for Docker and Podman sandboxes via `isolatedPaths` (for example `node_modules`) to prevent container installs from mutating host platform-specific dependencies. Update templates and init guidance to recommend this safer setup for dependency hooks, and document the behavior in the README.
