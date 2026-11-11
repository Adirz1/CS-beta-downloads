# Frogi Casework

Frogi Casework is an experimental SketchUp extension for exploring cabinet and casework designs. It brings cabinet editing, project data and draft production tools together for review. The package contains readable Ruby source.

## What you can do

- Create and edit cabinets with configurable dimensions, and make linked or independent copies.
- Browse library records, save project packages and reopen them for further work.
- Work with machining presets and export selected cabinet drilling data for review.
- Explore sheet nesting and generate draft part and sheet DXF exports from Production.
- Run project checks to help identify problems before continuing.

These tools support evaluation and planning. Draft exports are not machine programs or manufacturing approval.

## Getting started

The experimental 0.16.15 build is available on [Releases](https://github.com/Adirz1/CS-beta-downloads/releases). After installing a build you trust, open a new evaluation model in SketchUp and choose **Extensions > Frogi Casework > Open Toolbox**. Follow the release notes for package verification and installation details. If SketchUp blocks the extension or warns that it is untrusted, stop and do not weaken security settings to force it to load.

## Current limits

Native Windows and SketchUp compatibility, CAM, physical scanner behavior and manufacturer fit and machining acceptance are not yet validated. Use isolated test copies and keep backups; do not use the beta as a basis for production or manufacturing. Some older projects with unsupported or uncertifiable arc/profile definitions may fail to reopen as a whole, although their original bytes remain unchanged. Selective recovery is not available.
