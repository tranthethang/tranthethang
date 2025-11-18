---
description: Repository Information Overview
alwaysApply: true
---

# tranthethang Repository Information

## Summary

This is a personal portfolio/branding repository with minimal code content. The primary purpose is to serve as a personal GitHub profile with an introductory image asset and basic repository structure. The repository contains a portfolio banner with the tagline "CODE LIKE BREATH - TRANTHETHANG" displayed through SVG and PNG formats. The project includes WordPress gitignore configuration, suggesting potential integration with WordPress-based projects, though no WordPress files are currently committed.

## Structure

The repository maintains a simple, focused structure:

- **assets/**: Contains visual assets for the project
  - `intro.svg`: Scalable vector graphic with the portfolio introduction (1.87 MB)
  - `intro.png`: Rasterized version of the introduction image (889.74 KB)
- **Root Files**:
  - `.gitignore`: Standard WordPress gitignore template
  - `LICENSE`: GNU General Public License v3 (35 KB)
  - `README.md`: Repository entry point with embedded intro image

## Repository Type

**Type**: Personal Portfolio/Branding Repository  
**Primary Content**: Visual Assets and Configuration Files  
**Use Case**: GitHub Profile Showcase

## Configuration & Integration

**Version Control**: Git  
**License**: GNU General Public License v3.0  
**Gitignore Template**: WordPress (indicates potential WordPress ecosystem integration)

### WordPress Integration

The repository includes a comprehensive WordPress .gitignore that ignores:
- WordPress core files (`/wp-admin/`, `/wp-includes/`, core PHP files)
- Configuration files (`wp-config.php`)
- Theme and plugin directories
- Upload directories and logs
- This setup allows WordPress projects to be developed without committing core or user-generated files

## Key Resources

**Main Assets**:
- `README.md`: Entry point displaying the intro banner
- `assets/intro.svg`: Primary portfolio branding asset (vector format)
- `assets/intro.png`: Alternative portfolio branding asset (raster format)
- `LICENSE`: GPL v3 license document

**Configuration Files**:
- `.gitignore`: Version control exclusion rules
- `.git/`: Git repository metadata

## Usage & Operations

**Primary Purpose**: Serve as a personal GitHub profile landing page

**Display Method**: README.md embeds the intro SVG/PNG image using standard HTML picture element syntax for responsive image delivery

**Integration Points**: 
- GitHub profile integration through README.md display
- Potential foundation for WordPress-based projects (evidenced by .gitignore template)
- Can serve as a template or starting point for expanded portfolio/blog integration

## Notes

- The repository is intentionally minimal, prioritizing visual presentation over code complexity
- WordPress integration files are ignored by default, allowing this to be a clean portfolio repository while supporting WordPress development workflows
- Both SVG and PNG formats provided for maximum compatibility and performance optimization
