# PersistenceAI Releases

This document tracks all public releases of PersistenceAI.

## Current Version

**Latest Stable:** `1.0.13`

## Release Channels

- **Stable** - Production-ready releases
- **Beta** - Pre-release testing versions (coming soon)
- **Nightly** - Development builds (internal only)

---

## Release History

### [1.0.13] - December 30, 2025

**Type:** Patch Release

#### Fixed
- Fixed `@` and backslash commands in chat interface
- Improved command parsing and execution

---

### [1.0.12] - December 27, 2025

**Type:** Patch Release

#### Added
- Visual syntax highlighting improvements
- Enhanced file opening functionality
- New file navigation features

#### Fixed
- File explorer workspace saving improvements
- Better folder workspace persistence

---

### [1.0.11] - December 23, 2025

**Type:** Patch Release

#### Added
- Universal ESLint integration
- Enhanced code analysis capabilities
- Improved error detection and reporting

---

### [1.0.10] - December 20, 2025

**Type:** Patch Release

#### Changed
- Major version upgrade and core improvements
- Enhanced stability and performance

---

### [1.0.09] - December 16, 2025

**Type:** Patch Release

#### Added
- Toast notification system for upgrades
- Changelog settings and display
- Upgrade notification popup

---

### [1.0.08] - December 13, 2025

**Type:** Patch Release

#### Changed
- Model branding and naming updates
- Free model support improvements

---

### [1.0.07] - December 9, 2025

**Type:** Patch Release

#### Fixed
- Workspace directory saving and restoration
- Directory persistence across sessions
- File explorer directory tracking

---

### [1.0.06] - December 6, 2025

**Type:** Patch Release

#### Fixed
- Browse file and session restore functionality
- File restoration improvements

---

### [1.0.05] - December 2, 2025

**Type:** Patch Release

#### Added
- Completely reworked homepage UI
- Session restore functionality
- Enhanced home page experience

---

### [1.0.04] - November 28, 2025

**Type:** Patch Release

#### Changed
- Major version merge and integration
- Core system improvements

---

### [1.0.03] - November 25, 2025

**Type:** Patch Release

#### Added
- Chat scroll bar functionality
- Custom message formatting
- Enhanced chat interface

---

### [1.0.02] - November 21, 2025

**Type:** Patch Release

#### Added
- Enhanced agent system setup
- Improved view logging
- Additional agent capabilities

---

### [1.0.01] - November 14, 2025

**Type:** Initial Release

#### Features
- ✅ CLI with local model support (Ollama integration)
- ✅ Tab section improvements
- ✅ Draggable pane dividers
- ✅ Core terminal IDE functionality
- ✅ Multi-agent system foundation
- ✅ Persistent memory system
- ✅ Tool integration framework

#### Installation

**Windows:**
```powershell
iwr -useb https://persistence-ai.github.io/PersistenceAI/install | iex
```

**Linux/macOS:**
```bash
curl -fsSL https://persistence-ai.github.io/PersistenceAI/install | bash
```

#### Download

- **GitHub Releases:** [View Releases](https://github.com/Persistence-AI/Landing/releases)
- **Direct Download:** Available via install scripts

---

## Upcoming Releases

### Planned Features
- Package manager support (npm, bun, pnpm, Homebrew)
- Enhanced GitHub Actions integration
- Expanded documentation site
- Additional AI provider support
- Performance improvements

---

## Release Process

1. **Version Bump** - Update version in `package.json`
2. **Build Distribution** - Create platform-specific binaries
3. **Create GitHub Release** - Tag and publish release
4. **Update Changelog** - Document changes
5. **Deploy Website** - Update installation scripts

---

## Support

For questions about releases or to report issues:
- 📧 **Email:** PersistenceAI@proton.me
- 🐛 **Issues:** [GitHub Issues](https://github.com/Persistence-AI/Landing/issues)

---

**Note:** As a closed-source project, detailed technical changelogs are maintained internally. Public releases focus on user-facing features and improvements.
