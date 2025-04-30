# Website Icon Generator

This script automatically generates various icon files needed for a modern website from a source logo.

## Features

-   Creates multiple icon sizes required for different browsers and devices
-   Maintains aspect ratio and quality during resizing
-   Generates an Open Graph image with a gradient background
-   Creates a basic SVG silhouette for Safari pinned tabs
-   Preserves transparency in PNG icons

## Generated Files

The script creates the following files:

-   **favicon-16x16.png** - 16×16 favicon for browsers
-   **favicon-32x32.png** - 32×32 favicon for browsers
-   **favicon.ico** - multi-size ICO favicon for browsers
-   **apple-touch-icon.png** - 180×180 icon for iOS devices
-   **android-chrome-192x192.png** - 192×192 icon for Android devices
-   **android-chrome-512x512.png** - 512×512 icon for Android devices
-   **mstile-150x150.png** - 150×150 icon for Microsoft tiles
-   **og-image.jpg** - 1200×630 image for social media sharing
-   **safari-pinned-tab.svg** - SVG silhouette for Safari pinned tabs

## Requirements

-   Python 3.6 or higher
-   Pillow library

## Installation

1. Install the required dependencies:

```bash
pip install Pillow
```

Note: favicon.ico is now generated automatically by this script.
Consider using realfavicongenerator.net for more advanced manifest/HTML injection.
