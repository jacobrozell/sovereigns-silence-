# The Sovereign’s Silence

A short science fiction story published as a single static page for [GitHub Pages](https://jacobrozell.github.io/sovereigns-silence-/).

## What this is

This repo started as an experiment: take **real-world events**, feed them to an AI, and see how it **reinterprets** the material as story DNA. That exercise turned into a full short story aimed at the register of several favorite SF voices—**Philip K. Dick**, **Ray Bradbury**, **Roger Zelazny**, **Isaac Asimov**, and related shades of parable, myth, and cold bureaucratic irony.

The finished piece is **`index.html`** (required name for the site root). A duplicate copy also lives in the repo under the original long filename.

## How it was made

1. **Outline from the world** — Recent events went into **Gemini** to generate a **science fiction outline** inspired by what was happening in the world.
2. **Scrub** — All identifiable real-world data was **removed from the outline** so the fiction could stand on its own.
3. **Draft** — **Claude** wrote the story from the cleaned outline.
4. **Pass** — **Gemini** was used for **proofreading** and tightening.
5. **Iterate** — Over several days, **plot and structure choices** were revised by hand until the draft settled where it is now.

So the pipeline is roughly: **world → scrubbed outline → draft → proof → human iteration**.

## Outline (working document)

Behind the prose sits a **post-execution outline (rev 6)** aligned to the finished draft: act-by-act beats, notes on what changed between plan and execution (“execution deviations”), character architecture, ambient-monitor arc, and a **literary DNA** section (e.g. Vonnegut’s sardonic distance, PKD’s administered reality, Zelazny’s mythic self, Bradbury’s elegiac warmth). That document is a **companion artifact** to the story, not required to read the piece online.

If you add the styled outline to this repo as something like `outline.html`, you can link it from here as a second page on the same site.

## Local preview

Open `index.html` in a browser, or from this folder:

```bash
# example: Python built-in server
python -m http.server 8080
```

Then visit `http://localhost:8080/`.

## License / use

Unless you add a `LICENSE` file, default GitHub terms apply to the repo metadata only; clarify how you want the **story text** reused if you care about that.
