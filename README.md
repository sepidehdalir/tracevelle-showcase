# Tracevelle
### Your pattern. Perfectly still.

A native tracing lightbox for iPhone and iPad, designed and engineered by **Sepideh Javanbakht Dalir**.

**In development · Not released · Updated September 27, 2026.** Tracevelle is the approved provisional consumer brand; App Store name reservation is pending. This public repository contains curated product and engineering documentation. Commercial application source remains private.

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
| Native implementation | Initial implementation; QA in progress |
| Physical scale and paper suitability | Not verified; ruler/material checks required |
| StoreKit sandbox purchases | Not verified |
| Final icon and premium screenshot campaign | In production; no final assets published yet |
| App Store / release | Not submitted or released; no App Store link yet |

The final icon, tailored iPhone/iPad advertising campaign, release evidence and App Store link will be added as each is completed. Screenshots must use real app UI and demonstrate the relationship between a digital pattern, a locked illuminated screen and a physical traced result.

## About the developer

**Sepideh Javanbakht Dalir** · [arvinify.com](https://www.arvinify.com) · [hello@arvinify.com](mailto:hello@arvinify.com)

Product strategy, UX, iOS engineering, StoreKit integration, privacy, testing, branding, ASO and release preparation.

© 2026 Sepideh Javanbakht Dalir. All rights reserved.
