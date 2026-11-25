# Awesome Books About God and Jesus with Uncle Colby

The official website for the podcast *Awesome Books About God and Jesus with Uncle Colby*. Season one is a slow, chapter-by-chapter reading of Julian of Norwich's *Revelations of Divine Love*.

- **Listen:** [Apple Podcasts](https://podcasts.apple.com/us/podcast/awesome-books-about-god-and-jesus-with-uncle-colby/id1753998154) · [Spotify](https://podcasters.spotify.com/pod/show/uncle-colby)
- **Quotes:** every Julian quote on the site comes from Uncle Colby's own modern English translation.

## What's here

| File | What it is |
| --- | --- |
| `index.html` | The homepage: landing quote, Julian of Norwich, every episode with a quote, and About |
| `story.html` | "My story in pictures," linked from the About section |
| `img/` | Photos used on both pages |

It's a plain static site with no build step. Open `index.html` in a browser, or serve the folder with any static host (for example, GitHub Pages).

## Adding a new episode

In `index.html`, find the `RAW` episode list in the script near the bottom. Add one line per episode in this format:

```
episode|chapter|title|date|AppleEpisodeId|SpotifySlugSuffix|guest|quote
```

The "Where we are" progress bar and episode count update automatically from that list.
