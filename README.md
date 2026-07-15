# Zuzo Website Assets

Public repository of Zuzo frontend image and design assets, used as a
source for AI Studio to fetch files for rendering images on the website.

## Usage

Files are served over raw GitHub URLs, no authentication required:

```
https://raw.githubusercontent.com/geofforbes/Zuzo-Website-Assets/main/<filename>
```

Filenames containing spaces must be URL-encoded (spaces → `%20`), e.g.:

```
https://raw.githubusercontent.com/geofforbes/Zuzo-Website-Assets/main/Slack%20Icon.png
```

For files in sub-folders, include the folder in the path, e.g.:

```
https://raw.githubusercontent.com/geofforbes/Zuzo-Website-Assets/main/Client%20Logos/carousel-01.png
```

## Contents

### Website export images (zuzocard.com)

| File | Description |
|---|---|
| `apple-touch-icon-180.png` | Apple touch icon |
| `favicon-32.png`, `favicon-192.png` | Site favicons |
| `logo-header.png`, `logo-footer-white.png` | Site logos |
| `background-section.jpg` | Section background |
| `feature-icon-graphic.png` | Feature icon graphic |
| `card-feature-screenshot.webp` | Card feature screenshot |
| `marketplace-feature-screenshot.webp` | Marketplace feature screenshot |
| `teams-recognition-screenshot.webp` | Teams recognition screenshot |
| `social-proof-logos.png` | Social proof logo strip |

### Client Logos (`Client Logos/`)

| File | Description |
|---|---|
| `Client Logos/carousel-01.png` – `Client Logos/carousel-08.png` | Homepage carousel client logos |
| `Client Logos/carousel-09-peachpay-logo.png` | PeachPay logo (carousel) |

### Slack / Teams / brand assets

| File | Description |
|---|---|
| `Slack Icon.png`, `Slack logo SVG.svg` | Slack branding |
| `Slack Demo Message 1.png` | Slack demo message screenshot |
| `Slack Demo Message Caricature SVG.svg` | Slack demo message illustration |
| `Teams Icon.png` | Teams branding |
| `Teams Demo Message 1.png` | Teams demo message screenshot |
| `Teams-Slack Toggle (Standalone Design Element).html` | Standalone Teams/Slack toggle design element |
| `Zuzo Swoosh.png`, `Zuzo swirl SVG.svg` | Zuzo brand graphics |
| `Zuzo by Yoyo (Wordmark in White) [SVG].svg` | Zuzo by Yoyo wordmark, white, from the Brand Bank |

## Adding assets

Assets are added by copying files into this repo and pushing to `main`.
There is no build step — files are consumed directly from their raw URLs.
