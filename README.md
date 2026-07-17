# Zuzo Website Assets

Public repository of Zuzo frontend image, design, and content assets, used
as a source for AI Studio to fetch files for rendering images and copy on
the website.

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
https://raw.githubusercontent.com/geofforbes/Zuzo-Website-Assets/main/Client%20Logos/Calybre%20-%20Logo%20-%20Colour.svg
```

## Contents

### Website export images (zuzocard.com)

| File | Description |
|---|---|
| `apple-touch-icon-180.png` | Apple touch icon |
| `favicon-32.png`, `favicon-192.png` | Site favicons |
| `background-section.jpg` | Section background |
| `feature-icon-graphic.png` | Feature icon graphic |
| `card-feature-screenshot.webp` | Card feature screenshot |
| `marketplace-feature-screenshot.webp` | Marketplace feature screenshot |
| `social-proof-logos.png` | Social proof logo strip |

### Client Logos (`Client Logos/`)

Each client has a Colour and Greyscale variant, generally provided as both SVG and PNG, e.g. `Adept Advisory - Logo - Colour.svg` / `.png`. (`FASTA` and `Yoyo` currently have SVG only.)

| Client |
|---|
| Adept Advisory |
| Business Science Corporation |
| Calybre |
| Castlerock |
| FASTA |
| Kiron |
| Mama Money |
| Metrofibre |
| OnTec |
| Peach Payments |
| Strove |
| Wonga |
| Yoyo |

### Product Assets (`Product Assets/`)

| File | Description |
|---|---|
| `Product Assets/Slack Icon.png`, `Product Assets/Slack logo SVG.svg` | Slack branding |
| `Product Assets/Slack Demo Message 1.png` | Slack demo message screenshot |
| `Product Assets/Slack Demo Message Caricature SVG.svg` | Slack demo message illustration |
| `Product Assets/Teams Icon.png`, `Product Assets/Teams Icon SVG.svg` | Teams branding |
| `Product Assets/Teams Demo Message 1.png` | Teams demo message screenshot |
| `Product Assets/teams-recognition-screenshot.webp` | Teams recognition screenshot |
| `Product Assets/Example Nomination - Siya for Bongi - Slack.png`, `.svg` | Example nomination card, Slack |
| `Product Assets/Example Nomination - Jon to Kev 60Sixty - Teams.png`, `.svg` | Example nomination card, Teams |

### Other brand assets

| File | Description |
|---|---|
| `Teams-Slack Toggle (Standalone Design Element).html` | Standalone Teams/Slack toggle design element |
| `Zuzo Swoosh.png`, `Zuzo swirl SVG.svg` | Zuzo brand graphics |
| `Zuzo by Yoyo (Wordmark in White) [SVG].svg` | Zuzo by Yoyo wordmark, white, from the Brand Bank |
| `Zuzo App - Explainer Graphic.png` | Zuzo app explainer graphic |
| `Zuzo App - Home Screen.png` | Zuzo app home screen |
| `Zuzo in Slack - Explainer Graphic.png` | "Zuzo in Slack" walkthrough graphic (nomination + reward flow) |
| `Zuzo in Teams - Explainer Graphic.png` | "Zuzo in Teams" walkthrough graphic (nomination + reward flow) |

### Content

| File | Description |
|---|---|
| `testimonials.json` | Client testimonial quotes (quote, author, title, company) for the website to draw on |

## Adding assets

Assets are added by copying files into this repo and pushing to `main`.
There is no build step — files are consumed directly from their raw URLs.
