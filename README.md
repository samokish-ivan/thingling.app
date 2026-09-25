# Thingling – Feedback & Issue Tracker

This repository is used for reporting bugs, suggesting features, and tracking improvements for the Thingling Image Resizer & Optimizer.

PLEASE NOTE: Thingling is a simple, free-to-use image optimization tool with no ads, subscriptions, or paid features.

I may be slow to respond to issues, feature requests, or messages, so thank you for your patience and understanding!

🔗 https://thingling.app  
📷 Supports batch image optimization, resizing, focus-point cropping, format conversion, metadata editing, WebP export, custom filenames, ZIP downloads, and more.

---

## Report a Bug

Please open an issue and include:

- Steps to reproduce
- Example images, if possible
- Browser + operating system
- Expected result
- Actual result

## Suggest a Feature

Feature ideas are welcome.

Open a new issue and choose the **Feature Request** template.

---

# Changelog

All notable changes to Thingling are documented below.

## [v1.3] — 2026-09-25

### Added
- Support for large hero images while preserving original dimensions
- Adaptive batch processing with no fixed 50-image upload limit
- No fixed per-image file-size cap
- Custom ZIP filenames
- Single-image renaming
- Bulk filename patterns
- Duplicate filename protection
- Target file sizes with optional dimension reduction
- Before / after image comparison
- 100% output-size inspection
- Saved presets stored locally in the browser
- Retained originals for repeated exports
- Export cancellation and failed-image retry support

### Improved
- Sharper image previews rendered from original image pixels
- Sharper crop previews
- Large-image handling and browser resource management
- Export naming workflow
- Metadata handling
- Image format validation
- Mobile controls and responsiveness

### Changed
- Removed the maximum long-edge setting for large images
- Image processing now adapts more dynamically to available browser resources

## [v1.2] — 2026-03-17

### Added
- New Bulk Meta Editor tab (`data-mode="meta"`) with a dedicated queue and processing pipeline
- Batch metadata actions to strip all metadata or keep/edit metadata before export
- Metadata result badges, including `stripped` and `meta updated`
- Aspect ratio presets in Resize & Crop: 16:9, 4:3, 3:2, 1:1, 21:9, 9:16, 2:3, 4:5, 3:4, and Custom
- Ratio lock behavior with automatic width/height adjustment
- Per-image `Show / Edit Metadata` panels across all tabs
- Editable metadata fields for Title, Description, Author, Copyright, Keywords, and GPS stripping
- Read-only detected metadata display for Camera, Lens, ISO, Aperture, Shutter, Date, Resolution, and GPS
- Preserve original metadata option for Optimize, Resize, and Convert
- EXIF/XMP preservation and WebP reinjection with a ScaleFish processing tag, date, and user edits

## [v1.1] — 2026-03-03

### Added
- Auto-Optimizer feature

### Fixed
- Resizer & Crop layout

## [v1.0] — 2026-02-27

### Added
- Exact resize
- Auto-crop using object-fit
- Focus-point cropping
- Improved WebP compression
- Quality slider
- Drag-and-drop image uploads
- Batch processing
- Live previews
- Clean CLEAR reset
- 100% private, local-only image processing

---

🙏 Thank you for helping Thingling improve!
