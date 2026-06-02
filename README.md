# Zap

Zap is a minimal, performance-focused theme for [Ghost](https://github.com/TryGhost/Ghost), built to demonstrate Ghost's baseline performance without the overhead of heavy images, scripts, or large assets.

**Demo: https://zap.ghost.io**

# Instructions

1. [Download this theme](https://github.com/TryGhost/Zap/archive/main.zip)
2. Log into Ghost, and go to the `Design` settings area to upload the zip file

# Development

Zap is intentionally small. You can edit the Handlebars templates in the theme root and the stylesheet in `/assets/screen.css`.

From the theme's root directory:

```bash
# Enable the package manager pinned in package.json
corepack enable

# Install dependencies
pnpm install

# Check theme compatibility
pnpm test
```

# Contribution

If you're looking to contribute or raise an issue, head over to the [TryGhost/Zap](https://github.com/TryGhost/Zap) repository.

# Copyright & License

Copyright (c) 2013-2026 Ghost Foundation - Released under the MIT license.
