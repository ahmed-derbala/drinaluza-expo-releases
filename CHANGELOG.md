## [1.70.1] - 22 september 2026

### Changed
- Switched the app config to the production flavor (production name, icon, Android package, link scheme, and NODE_ENV).

## [1.69.0] - 22 september 2026

### Added
- Added docs/.env.example template documenting the required public environment variables.

### Changed
- Pointed the release scripts (APK publishing and changelog sync) to the drinaluza-releases repository.
- Allowed docs/.env.example through .gitignore and .easignore while keeping real .env files ignored.

## [1.65.0] - 21 september 2026

### Enhanced
- Improved the product feed card layout with better spacing and visual hierarchy.
- Updated Expo SDK packages (expo, expo-router, expo-updates, expo-notifications, expo-location, expo-sharing, expo-build-properties) for stability and compatibility.
- Improved Android release build reliability by enabling the new architecture with SDK auto-download and limiting parallel build jobs to prevent out-of-memory errors.

### Fixed
- Fixed the product feed card layout on mobile devices by adjusting padding and margin values to ensure consistent spacing across all screen sizes.
- Fixed the in-app update check URL to use the renamed drinaluza-releases repository.
- Fixed the changelog publishing step and wired it into the production APK build.
- Fixed the development APK build environment flag (local to development).


