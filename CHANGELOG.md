# Changelog

## [0.1.0] - 2026-01-05

### Changes

- 02b763db feat: electron automation, ui improvement, and bug fixes (#106)
- 2507a023 feat: Add MPC Autofill community art source
- cf850025 feat: Setup standalone electron app
- 817e4846 fix: change import to plugin
- bc4750d2 fix: Add guide options to adjust length
- 0323559c feat: Add advanced editor card image control and rebuild page view to use webgl canvas for real time rendering and animations
- 4e39f633 fix: Issue where dragging a card down caused the page to scroll (#97)
- 17d0e27b feat: Set up full DFC support
- db9667ca feat: Add bulk import support for server local scryfall lookups
- ee232785 feat: Set up full DFC support
- f5766be6 compressed image
- 6e701ebd fixed styling and changed button location
- 0fd55f1d Add Card Back button to upload section
- d2da28ae feat: Add moxfield import support
- 4d8f5c05 feat: Add Archidekt deck import with category-based filtering
- c7b11676 cleanup: optimize PDF generation
- 339c584f feat: unify upload image buttons, and PDF/page logic, and improve bleed generation UI/controls
- 96417848 cleanup: split some overly large files, remove unused imports, split modules, etc
- 0fc2959e feat: add multiple card drag support
- 534ce01d feat: add local caching for card metadata
- 3f78706b feat: support per card bleed settings, more control over bleed, multi-select, etc
- 7b43800e feat: add local cache that isn't cleared on clear cards to optimize card loads across sessions
- c6f9ab8e feat: improve DFC support
- 2a919533 feat: Add undo/redo buttons and tracking
- dfd08b22 cleanup: dedup image/streamRouter endpoints
- b072d12e Add placeholder cards for failed Scryfall lookups
- 58ad40bc fix: Add fallback to streaming api on collection failure.
- 6c3c362b fix: cancel workers processing on clear cards/reset app data to immediately free resources
- 887673cc fix: Make sure language setting gets language specific art if available on import and use collection api for metadata fetch
- 20818c76 Use scryfall collection api endpoint for text box import