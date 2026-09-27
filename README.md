# Tracevelle
### Your pattern. Perfectly still.

<img src="assets/icon.png" width="100" alt="Tracevelle layered botanical tracing-paper icon">

A native tracing lightbox for iPhone and iPad, designed and engineered by **Sepideh Javanbakht Dalir**.

**In development · Not released · Updated September 27, 2026.** Apple has accepted the name Tracevelle: Tracing Lightbox; the app is in Prepare for Submission. This public repository contains curated product and engineering documentation. Commercial application source remains private.

## A focused tool for physical making

Prepare a small embroidery reference, stencil, lettering study or craft pattern beneath suitable paper. The workflow is deliberately simple:

**Import → Size → Position → Lock → Trace**

The implementation includes Photos/Files image import, resize/rotate/mirror controls, contrast and outline adjustment, ruler-guided calibration, an in-app gesture lock and local current-work recovery. It is a physical tracing utility, with no AI generation, AR tracking, drawing suite or account.

## Engineering

- **Swift and SwiftUI**, Universal iPhone/iPad, deployment target iOS/iPadOS 15.
- **PhotosUI, ImageIO and Core Image** for selected-image import, orientation-correct rendering and native adjustments. Original image bytes are preserved.
- **Codable and atomic local file writes** for current work, named projects and reusable settings.
- **UIKit lifecycle integration** to restore temporary screen brightness and awake settings.
- **StoreKit 2** for a one-time Lifetime Pro purchase, verified entitlements, restore and transaction updates.
- **XCTest** for calibration calculations, display invalidation and persistence integrity. Build/runtime results are recorded separately from physical measurements.

The canvas retains the same geometry when editing controls disappear. Calibration is tied to display/window configuration instead of assuming a universal screen density. Saved originals are immutable, and a failed import does not intentionally replace existing work.

## Privacy and pricing approach

Patterns stay on device. No backend, account, ads or analytics SDK. Apple handles payments. System device backups may include local app data.

The complete single-image tracing workflow and current-work recovery are free. Lifetime Pro adds a named pattern library and reusable size/contrast presets. Pricing is a commercial experiment, not evidence of demand.

## Production status

| Area | Status |
| --- | --- |
| Product strategy | Frozen focused V1; existing portfolio research informs the experiment |
| Native implementation | Initial implementation; simulator build and signed archive succeeded; QA in progress |
| Automated core checks | Three host XCTest cases passed September 27, 2026 |
| Physical scale and paper suitability | Not verified; ruler/material checks required |
| StoreKit sandbox purchases | Not verified |
| Icon | Production direction selected and inspected at 40px |
| Premium screenshot campaign | In production; final real-UI campaign not published |
| App Store / release | Not submitted or released; no App Store link yet |

The tailored iPhone/iPad advertising campaign, release evidence and App Store link will be added as each is completed. Screenshots must use real app UI and demonstrate the relationship between a digital pattern, a locked illuminated screen and a physical traced result.

## Visual identity

Botanical ink, warm linen and burnished copper connect the interface to physical craft. This generated editorial still life is supporting artwork, not an app screenshot or material-performance evidence.

<img src="assets/craft-still-life.png" width="420" alt="Embroidery and tracing-paper campaign artwork">

## About the developer

**Sepideh Javanbakht Dalir** · [arvinify.com](https://www.arvinify.com) · [hello@arvinify.com](mailto:hello@arvinify.com)

Product strategy, UX, iOS engineering, StoreKit integration, privacy, testing, branding, ASO and release preparation.

© 2026 Sepideh Javanbakht Dalir. All rights reserved.
