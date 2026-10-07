# Clip Studio

Clip Studio is a browser-based tool for building AI image prompts, planning storyboards, and finding free video-generation Spaces.

## Features

- Build polished image and video prompts from a simple idea
- Generate images through Pollinations AI
- Create a multi-shot storyboard
- Copy prompts for use in external AI generators
- Works entirely in the browser with no backend or API key

## Run locally

Open `index.html` directly in a browser, or serve the repository locally:

```bash
python3 -m http.server 8000
```

Then visit http://localhost:8000.

## Deploy to GitHub Pages

1. Push this repository to GitHub.
2. Open **Settings → Pages**.
3. Set **Source** to **GitHub Actions**.
4. Push to the `main` branch; GitHub Actions will publish the site.

The live site will be available at:

`https://forotherwork786-stack.github.io/ai-video-maker-/`

## Notes

- The image generator and external video links depend on third-party services.
- If an image request fails, try again later or use a different prompt.
- GitHub Pages serves the website as static content; no secret keys are required.
