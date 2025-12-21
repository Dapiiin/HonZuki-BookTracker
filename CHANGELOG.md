# Changelog

All notable changes to HonZuki will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.1.0] - 2025-12-21 (Current Release)

### ✨ Added
- **Series Management System** - First-class series entities with dedicated pages
- **Series Statistics** - Auto-tracked owned, read, and reading counts
- **Visual Progress Bars** - Multi-segment bars showing series completion
- **Series Status Tracking** - Mark series as Ongoing or Completed
- **Quick Series Updates** - "+1 Book Released" button for ongoing series
- **Missing Books Indicator** - See how many books needed to complete series
- **Genre Management** - Rename and delete genres from genre pages
- **Enhanced Sharing** - More flexible sharing options with better UI
- **Theme Import/Export** - Share custom themes via JSON
- **Reading Speed Settings** - Configure personal reading speed for estimates
- **Adaptive Backgrounds** - Dynamic backgrounds based on book cover colors
- **Lighten/Darken Filters** - Options to adjust adaptive background colors
- **14+ Font Options** - Expanded typography choices including OpenDyslexic
- **Command Palette** - Quick navigation with Cmd/Ctrl + K
- **Offline Indicator** - Visual feedback for offline status

### 🔧 Improved
- **Performance** - Optimized theme loading to prevent color flash
- **Book Cards** - Better visual design and hover effects
- **Search** - Faster and more accurate search results
- **Statistics Page** - Enhanced charts and metrics
- **Mobile Experience** - Better touch interactions and responsive design
- **Guest Mode** - Full feature parity with authenticated mode
- **Data Import/Export** - Support for both CSV and JSON formats

### 🐛 Fixed
- Theme persistence across page reloads
- Series ordering and alphabetical sorting
- Import/export data integrity issues
- Mobile menu navigation issues
- Color extraction for books without covers

### ⚠️ Known Issues / Current Status
- 🔴 **Authentication Disabled** - All users must use Guest Mode
- ❌ **No Cloud Sync** - Data stored locally only (in browser localStorage)
- ❌ **No Sharing Features** - Public share links disabled
- ✅ **All Core Features Work** - Full functionality in Guest Mode
- 📋 **Export Regularly** - Back up your library via Settings → Export
- 🔜 **Authentication Fix Planned** - Expected in v1.2.0

## [1.0.0] - 2025-11-15

### 🎉 Initial Release

#### Core Features
- **Library Management** - Add, edit, and delete books
- **ISBN Barcode Scanner** - Auto-fetch book metadata
- **Custom Shelves** - Organize books into collections
- **Reading Status** - Track reading progress and dates
- **Multiple Authors & Genres** - Support for multiple tags per book
- **Search & Filter** - Find books by various criteria
- **Wishlist** - Separate wishlist management
- **Statistics** - Basic stats and collection metrics

#### User Features
- **Firebase Authentication** - Email/password login
- **Cloud Sync** - Real-time Firestore sync
- **Guest Mode** - Anonymous usage with localStorage
- **Profile Settings** - Manage account details
- **Data Export** - CSV export functionality

#### UI/UX
- **Responsive Design** - Mobile, tablet, and desktop support
- **Grid/List Views** - Multiple view options
- **Theme Customization** - Custom accent and background colors
- **Progressive Web App** - Install as native app
- **Offline Support** - Core features work offline

#### Technical
**Next.js 15.3** - App Router architecture
**TypeScript** - Full type safety
**Tailwind CSS** - Utility-first styling
**shadcn/ui** - Component library
**Firebase 11.9** - Backend services

---

For detailed information about each release, see the [Releases](../../releases) page.
