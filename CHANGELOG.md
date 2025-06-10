# 🏷️ Changelog

<sub><i>All notable changes to this project will be documented in this file.</i></sub>

<!-- CHANGELOG_ENTRY -->
## [v0.0.10] - 2025-06-10

### ✨ Features
- Added model management and validation functionality
- Implemented Electron Updater with manual download capability
- Added auto-scroll to bottom for streaming chat messages
- Added pagination for payment history
- Refactored Plan page for better user experience

### 🐛 Bug Fixes
- Fixed API key display and security (hiding last 4 characters)
- Fixed convention-incompatible filenames
- Fixed API key handling issues
- Fixed release version and Slack notes retrieval in publish workflow

### 📦 Improvements
- Enhanced release workflow to handle multiple DMG file types for macOS
- Updated release workflow to trigger on published releases
- Added manual dispatch option for releases
- Improved overall release process automation

---

## [v0.0.9] - 2025-06-10

v0.0.9

---

## [v0.0.8] - 2025-06-06

### ✨ Features
- Added tray icon support for better app accessibility
- Implemented dashboard usage tracking and analytics
- Added theme support in private routes and header components
- Integrated payment history view
- Added related pages for payment flow and Stripe integration
- Implemented version checking and management system
- Added AI model switcher functionality
- Implemented API key management and enhanced onboarding flow
- Added sign-up flow and improved sign-in UI
- Implemented markdown renderer and integrated chat flow
- Added floating window functionality
- Implemented mini chat bar UI
- Added Google sign-in flow with provider parameter

### 🐛 Bug Fixes
- Fixed selected content clipping issue
- Added delay before reading content from clipboard to prevent race conditions
- Fixed navigation loop issue in app configuration
- Fixed auto call update shortcut functionality
- Added retry and refresh token handling for 401 errors
- Fixed button styling issues in Mantine components
- Fixed loading state when login fails
- Fixed refresh token issues in the app

### 📦 Improvements
- Enhanced app configuration and database initialization with clean migration logic
- Updated macOS build process to support signing and notarizing packages
- Refactored dashboard and improved current model display
- Streamlined chat UI and improved model handling
- Enhanced floating window creation and handling
- Improved auth flow with email-based sign-in
- Optimized database structure for type safety
- Enhanced GitHub workflows for release and pull request processes
- Improved native dependency rebuild process
- Replaced nut-js with robotjs for better clipboard operations
- Refactored project structure and upgraded to version 2 using kysely

---


## [v0.0.7] - 2025-06-06

### ✨ Features

- Base functionality with AI assistant
- Compatible with macOS

### 🚧 Upcoming

- Windows and Linux support coming soon

---

## [v0.0.6] - 2025-06-05

### Initial Release

- Base functionality with AI assistant
- Compatible with macOS (Windows, Linux support coming soon)
