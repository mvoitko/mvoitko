# CLAUDE.md

## Repository Overview

This is a **GitHub profile README repository** (`mvoitko/mvoitko`). The special-name repo displays its `README.md` on the owner's GitHub profile page at https://github.com/mvoitko.

## Structure

```
.
└── README.md    # GitHub profile page (HTML format)
```

The repository contains a single file: `README.md`, written in HTML (not Markdown), which renders as the GitHub profile landing page.

## README.md Format

- The file uses raw HTML with inline styling (`align="center"`, etc.)
- Sections: name/title, bio, skills, and contact links
- Social badges use `shields.io` for Twitter and Stack Overflow
- Contact icons link to external social image assets hosted on GitHub (`gauravghongde/social-icons`)

## Development Workflow

- **Default branch:** `master`
- **No build system, tests, linters, or CI/CD** — this is a static content repo
- Changes are made directly to `README.md`
- Commit messages follow a simple descriptive style (e.g., "Update README.md", "Fix Twitter name")

## Key Conventions

- Keep `README.md` in HTML format for layout control (centered alignment, image sizing)
- Profile content includes: bio, skills list, and social/contact links
- No other files should be added unless required for GitHub profile features (e.g., GitHub Actions for dynamic content)

## When Making Changes

1. Edit `README.md` directly
2. Verify HTML is well-formed — GitHub renders it in a constrained environment
3. Test that external image/badge URLs are valid
4. Use concise commit messages describing the change
