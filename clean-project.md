# Clean Project Tool

The Clean Project window scans your project to detect unused assets.

---

## Scan Options

- Include scenes in Build Settings  
- Include currently open scenes  
- Include Resources folder assets (conservative)

Resources folder assets are treated as "used" by default to avoid false positives.

---

## Safety Rules

- Assets are never deleted
- Assets are only moved
- Original paths are stored in a manifest file
