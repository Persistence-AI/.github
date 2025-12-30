# Repository Visibility Guidelines

## Project Status

**PersistenceAI is currently a closed-source project.** The core codebase is proprietary and remains private.

## Repository Visibility Policy

### Public Repositories

The following types of repositories should be **public**:

- ✅ **Website/Documentation** - Public-facing content (e.g., `Landing`)
- ✅ **Install Scripts** - Installation and deployment scripts
- ✅ **Select Tools** - Specific tools or utilities that may be open-sourced
- ✅ **Examples/Templates** - Example code, templates, or starter projects
- ✅ **Organization Files** - `.github` repository with organization-wide files

### Private Repositories

The following should remain **private**:

- 🔒 **Core Codebase** - Main application code
- 🔒 **Proprietary Features** - Closed-source features and implementations
- 🔒 **Internal Tools** - Development and build tools
- 🔒 **Configuration** - Internal configuration and secrets
- 🔒 **Research/Development** - Experimental or in-development features

## Selective Open Source

Some components may be selectively open-sourced in the future:

- **Criteria:** Components that don't expose proprietary logic
- **Examples:** CLI wrappers, example integrations, documentation tools
- **Process:** Each component will be evaluated individually
- **Licensing:** Will use appropriate open-source licenses when released

## Organization Settings

### Default Repository Visibility

**Recommended:** Set organization default to **Private**

1. Go to **Settings** → **General**
2. Scroll to **Repository creation**
3. Set **Default repository visibility** to **Private**

This ensures new repositories are private by default, requiring explicit action to make them public.

### Repository Transfer

When transferring repositories:
- **Public → Private:** Always allowed
- **Private → Public:** Requires careful review to ensure no proprietary code is exposed

## Best Practices

1. **Review before making public:** Always review code before making a repository public
2. **Use `.gitignore`:** Ensure sensitive files are never committed
3. **Separate concerns:** Keep public and private code in separate repositories
4. **Document decisions:** Document why a repository is public or private
5. **Regular audits:** Periodically review repository visibility settings

## Questions?

If unsure about repository visibility:
- Contact: PersistenceAI@proton.me
- Review this document
- Consider: "Does this expose proprietary logic or sensitive information?"

---

**Last Updated:** Based on current project status
