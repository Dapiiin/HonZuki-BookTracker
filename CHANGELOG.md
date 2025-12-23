# Changelog

All notable changes to HonZuki will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.3.0] - 2025-12-23 (Current Release)

### ✨ Added
- **Advance Shelf Management** - Comprehensive tools for organizing your shelves
  - **"Add Books" Page** - Dedicated page (`/shelves/[id]/add`) to bulk add books with filtering and local search
  - **Shelf Selection UI** - Persistent bottom bar for managing books within a shelf
    - Select Mode with "Select All" / "Deselect All" options
    - Bulk "Remove" and "Add to Another Shelf" actions
  - **Smart Creation** - "Add books immediately" option when creating a new shelf
- **Shelf Search** - Real-time client-side search bar within shelf details to find books by title or author


### 🎨 Redesigned


### 🔧 Improved
- **Library Features**
  - **In-Page Search** - Filter books by title, author, publisher directly in the library view
  - **Enhanced Selection** - "Select All" option, persistent selection state, and improved UI

### 🐛 Fixed
- **Shelf Filtering** - Fixed bug where viewing a shelf displayed all books from the library
- **Shelf Sorting** - Shelves are now correctly sorted alphabetically (case-insensitive)


### ⚠️ Known Issues / Current Status
- 🔴 **Authentication Disabled** - All users must use Guest Mode
- ❌ **No Cloud Sync** - Data stored locally only (in browser localStorage)
- ❌ **No Sharing Features** - Public share links disabled
- ✅ **All Core Features Work** - Full functionality in Guest Mode
- 📋 **Export Regularly** - Back up your library via Settings → Export
- 🔜 **Authentication Fix Planned** - Expected in future release

---

For detailed information about each release, see the [Releases](../../releases) page.