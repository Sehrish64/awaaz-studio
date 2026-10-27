# Awaaz Studio

Free, open source text-to-speech studio for the Gemini API. One HTML file, no build step, no backend.
Not affiliated with Google.

## Features
- One-voice and two-voice (dialogue) modes, 30 Gemini voices
- Style box ("slow, dramatic storyteller")
- Long scripts are split into parts and joined automatically
- Roman Urdu to Urdu script button (better pronunciation)
- Play in browser and download WAV

## Use it
1. Get a free key at https://aistudio.google.com/apikey
2. Open `index.html` (double-click, or host it), paste the key, write a script, press Generate.

The key stays in your browser (localStorage) and is sent only to Google. Free-tier limits are set by Google and can change.

## Two voices
Set the two speaker names, then write lines like:
```
Maa: Mera bacha wapas kar do.
Magarmach: Pehle andaza lagao.
```

## Deploy free on GitHub Pages
1. Push this folder to a GitHub repo.
2. Settings → Pages → Source: **GitHub Actions**.
3. Push to `main`. The included workflow publishes the site.

## Notes
- Models are previews and names can change. Edit the `<select id="model">` options in `index.html`.
- Audio is 24 kHz, 16-bit, mono PCM wrapped as WAV.

MIT License.
