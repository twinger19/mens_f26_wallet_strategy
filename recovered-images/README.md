# Recovered mood images

These are **your real mood images that my commits deleted.** Nothing is lost — they are all here, and also in git history.

## What happened

You committed real imagery in `b120cbf`, `8b768f1`, `7cdf10e` and `1945309`. I did not pull before my next change, so when I renamed mood files to match the new F27 callouts (`a07da63`, `f119451`, `dedae1c`), git recorded your images as deletions and wrote fresh placeholders over them.

| Brand | Status |
|---|---|
| **Cole Haan** | **Fully restored.** Callouts, filenames and your six real images are back as they were. |
| **Levi's** | Never touched. Your six real images are intact. |
| Calvin Klein | 4 real images recovered here — the callouts changed, so they need re-placing |
| Kenneth Cole | 6 real images recovered here — same |
| Tommy Hilfiger | 3 real images recovered here — same |

## Why these need re-placing rather than auto-restoring

You sourced these against the **old** captions. Cole Haan reverted to its old captions, so its images map straight back. The other three have new callouts, so the old images no longer match their slots. The filename here is the **old caption** the image was chosen for — use it to decide where each one now belongs.

## Mapping — old caption these were sourced for

### Calvin Klein → new callouts are Subdued Logoing / Metal Details / ID Window Updates / City Living / Clean Utility / Transitional Dressing
| Recovered file (old caption) | Format |
|---|---|
| `02-negative-space-and-editorial-grid.jpg` | PSD 440×440 |
| `03-ostrich-exotics-beyond-croco.jpg` | WebP 1000×1250 |
| `04-tonal-monogram-jacquard.jpg` | WebP 1728×2275 |
| `06-slim-and-magsafe.jpg` | AVIF 2500×2500 |

### Kenneth Cole → new callouts are Holiday Dress / Mixed Media / Technology / Slim Constructions / Gifting / Added Value
| Recovered file (old caption) | Format |
|---|---|
| `01-office-utility-evening-street.jpg` | WebP 800×682 |
| `02-magnet-array-and-phone-mount.jpg` | WebP 1040×1300 |
| `03-matte-gunmetal-engineered-detail.jpg` | WebP 800×984 |
| `04-midnight-navy-and-slate.jpg` | WebP 2000×2667 |
| `05-interior-accent-colour-pop.jpg` | WebP 2000×2667 |
| `06-tracker-cable-and-transit-organisation.jpg` | WebP 1024×1024 |

Likely still usable: `02-magnet-array` → **Technology** or **Slim Constructions**; `06-tracker-cable` → **Technology** or **Added Value**.

### Tommy Hilfiger → new callouts are Exotics / Tommy Touches / Super Prep / Craft Details / Dress Hardware / Magnets
| Recovered file (old caption) | Format |
|---|---|
| `01-prep-heritage-pushed-forward.jpg` | WebP 791×1054 |
| `02-refined-casual-casual-sport.jpg` | WebP 1728×2304 |
| `04-brushed-wool-and-felted-surface.jpg` | WebP 1728×2304 |

Likely still usable: `01-prep-heritage` → **Super Prep**; `04-brushed-wool` → **Craft Details**.

## How to re-place one

Copy it into the brand's mood folder under the **new** filename, replacing the placeholder:

```
cp recovered-images/kenneth-cole/02-magnet-array-and-phone-mount.jpg \
   images/07-moodboards/kenneth-cole/03-technology.jpg
```

Delete this whole folder once you are done — the originals stay in git history either way.

## One thing to fix while you are here

Several of these are **AVIF, WebP or PSD saved with a `.jpg` extension**. Browsers sniff the content so they display fine, but the PSD (1.9MB for a 440×440 tile) will not render everywhere and is 80× heavier than it needs to be. Worth re-exporting as real JPEGs at ~640–1000px square.
