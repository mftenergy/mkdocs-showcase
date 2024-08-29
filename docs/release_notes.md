# Changelog

## Material for MkDocs

### 9.5.33 <small>August 23, 2024</small> { id="9.5.33" }

- Fixed #7453: Incorrect position of tooltip when sorting table

### 9.5.32 <small>August 19, 2024</small> { id="9.5.32" }

- Fixed RXSS vulnerability via deep link in search results
- Added support for fetching latest release from GitLab

### 9.5.31 <small>August 2, 2024</small> { id="9.5.31" }

- Fixed #7405: DockerHub missing images > 9.5.27 due to change in Alpine/APK

### 9.5.30 <small>July 23, 2024</small> { id="9.5.30" }

- Fixed #7380: Navigation icons disappearing on hover in Safari
- Fixed #7367: Blog readtime computation includes SVG text content

### 9.5.29 <small>July 14, 2024</small> { id="9.5.29" }

- Updated Galician translations
- Fixed #7362: Annotations in figure captions rendering incorrectly

### 9.5.28 <small>July 2, 2024</small> { id="9.5.28" }

- Fixed #7313: Improved tooltips mounted in sidebar when feature is disabled

### 9.5.27 <small>June 16, 2024</small> { id="9.5.27" }

- Updated Estonian translations

### 9.5.26 <small>June 6, 2024</small> { id="9.5.26" }

- Fixed #7232: Tab switches on scroll when linking tabs (9.5.19 regression)
- Fixed #7230: Blog author avatar broken when referring to local file

### 9.5.25 <small>May 27, 2024</small> { id="9.5.25" }

- Fixed #7209: Tags plugin crashing on numeric tags

### 9.5.24 <small>May 20, 2024</small> { id="9.5.24" }

- Fixed #7187: Version selector title rendering issue

### 9.5.23 <small>May 15, 2024</small> { id="9.5.23" }

- Fixed #7183: Edge case in anchor navigation when using instant navigation
- Fixed #6436: Version selector not showing version alias

### 9.5.22 <small>May 12, 2024</small> { id="9.5.22" }

- Fixed #7170: Copy button adds empty lines for line spans (9.5.18 regression)
- Fixed #7160: Version switching doesn't stay on page (9.5.5 regression)
- Fixed #5619: Links in Mermaid.js diagrams not discernible

### 9.5.21 <small>May 3, 2024</small> { id="9.5.21" }

- Fixed #7133: Ensure latest version of Mermaid.js is used
- Fixed #7125: Added warning for dotfiles in info plugin

### 9.5.20 <small>April 29, 2024</small> { id="9.5.20" }

- Fixed deprecation warning in privacy plugin (9.5.19 regression)
- Fixed #7119: Tags plugin emits deprecation warning (9.5.19 regression)
- Fixed #7118: Social plugin crashes if fonts are disabled (9.5.19 regression)
- Fixed #7085: Social plugin crashes on Windows when downloading fonts

### 9.5.19 <small>April 25, 2024</small> { id="9.5.19" }

- Updated MkDocs to 1.6 and limited version to < 2
- Updated Docker image to latest Alpine Linux
- Removed `setup.py`, now that GitHub fully understands `pyproject.toml`
- Improved interop of social plugin with third-party MkDocs themes
- Fixed #7099: Blog reading time not rendered correctly for Japanese
- Fixed #7097: Improved resilience of tags plugin when no tags are given
- Fixed #7090: Active tab indicator in nested content tabs rendering bug

### 9.5.18 <small>April 16, 2024</small> { id="9.5.18" }

- Refactored tooltips implementation to fix positioning issues
- Fixed #7044: Rendering glitch when hovering contributor avatar in Chrome
- Fixed #7043: Highlighted lines in code blocks cutoff on mobile
- Fixed #6910: Incorrect position of tooltip for page status in sidebar
- Fixed #6760: Incorrect position and overly long tooltip in tables
- Fixed #6488: Incorrect position and cutoff tooltip in content tabs

### 9.5.17 <small>April 2, 2024</small> { id="9.5.17" }

- Updated Serbian translations
- Fixed #7003: Confusing keyboard interaction for palette toggle
- Fixed #7001: Blog posts now show time by default (9.5.16 regression)
- Fixed edge case in backport of social plugin font loading logic

### 9.5.16 <small>March 31, 2024</small> { id="9.5.16" }

- Updated Russian translations
- Improved error handling and reporting in social plugin
- Improved error handling and reporting in privacy plugin
- Fixed blog plugin not allowing to use time in format strings
- Fixed #6983: Social plugin crashes because of Google Fonts API change

### 9.5.15 <small>March 23, 2024</small> { id="9.5.15" }

- Reverted fix for transparent iframes (9.5.14)
- Fixed #6929: Interference of social plugin and auto dark mode
- Fixed #6938: Giscus shows dark background in light mode (9.5.14 regression)