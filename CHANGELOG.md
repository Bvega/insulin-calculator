# Changelog

All notable changes to the Personal Insulin Dosage Calculator.

## [2.0.0] - 2026-01-26

### Added
- **Admin Panel** with PIN protection (default: 1234)
- **localStorage persistence** for all settings
- **Editable values** for Basaglar, Humalog (all meals), and Correction Scale
- **PIN change functionality** in admin settings
- **Reset to defaults** option
- **Last updated timestamp** display
- **Close on outside click** for admin panel

### Improved
- Enhanced mobile responsiveness with tablet (768px) and phone (480px) breakpoints
- Better button layouts on mobile devices
- Improved table formatting for small screens
- Added iOS web app meta tags for home screen installation

## [1.0.0] - 2026-01-05

### Added
- Initial release with mobile-responsive design
- Basaglar (long-acting) daily dose display
- Humalog (rapid-acting) calculator for:
  - Breakfast doses (10 blood sugar ranges)
  - Lunch doses (10 blood sugar ranges)
  - Dinner doses (10 blood sugar ranges)
- Correction scale for forgotten doses (7 ranges)
- Two calculation scenarios:
  - Normal pre-meal dose
  - Forgotten dose (during meal or >1 hour after)
- Visual dose tables with highlighting
- Low blood sugar warning for readings <70 mg/dL
- Responsive design for desktop and mobile

---

## Version Numbering

This project follows [Semantic Versioning](https://semver.org/):
- **MAJOR**: Breaking changes or significant feature overhauls
- **MINOR**: New features, backward-compatible
- **PATCH**: Bug fixes, backward-compatible
