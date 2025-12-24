# Changelog

All notable changes to HonZuki will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.3.1] - 2025-12-24
### ✨ Added
- **Book Details** - Added "Move to Wishlist" option in the "More" menu to send a book back to your wishlist (resets reading progress)

### 🔧 Improved
- **Add Book**
  - **Duplicate Prevention** - Added strict, aggressive duplicate prevention. It effectively normalizes titles (ignoring "Vol", "Volume", "Book", "Part") to catch matches like "The Boxer Vol 3" and "The Boxer 3", while correctly distinguishing distinct editions like "The Boxer Novel".
  - **Smart Search** - Search results now automatically filter out books you already own or have wishlisted. The system now fetches **80 books** per search to ensure you still get 40 relevant results even after filtering.
- **Library**
  - **Filter UX** - Removed redundant "Genre" filter (since dedicated page exists) and added scrolling to filter dropdowns for better handling of long lists
- **Add Book**
  - **Defaults** - "Format" field now defaults to "Paperback"
- **Search**
  - **Series Parsing** - Title search now prioritizes matching against your *existing* library series, preventing duplicate or mismatched series entries

### 🐛 Fixed
- **Navigation Scroll** - Fixed issue where pages would remain scrolled down after navigation (e.g., after adding a book to wishlist)


### ⚠️ Known Issues / Current Status
- 🔴 **Authentication Disabled** - All users must use Guest Mode
- ❌ **No Cloud Sync** - Data stored locally only (in browser localStorage)
- ❌ **No Sharing Features** - Public share links disabled
- ✅ **All Core Features Work** - Full functionality in Guest Mode
- 📋 **Export Regularly** - Back up your library via Settings → Export
- 🔜 **Authentication Fix Planned** - Expected in future release

---

For detailed information about each release, see the [Releases](../../releases) page.
