# SolfaScribe — Sheet Music to Tonic Solfa Converter

A free, client-side web app that uses Claude AI (Anthropic) to convert sheet music (PDF or image) into SATB Tonic Solfa notation for choirs.

## Features
- Upload PDF or image sheet music (multi-page PDFs supported)
- Converts to Soprano, Alto, Tenor, Bass (SATB) tonic solfa
- Detects key signature and time signature automatically
- Supports standard (d r m), full word (do re mi), and numbered (1 2 3) formats
- Download output as PDF or TXT, or copy to clipboard
- 100% client-side — your sheet music never leaves your browser
- Free to host on Cloudflare Pages

## Setup
1. Fork or clone this repo
2. Deploy to Cloudflare Pages (connect GitHub repo → auto-deploy)
3. Users bring their own Anthropic API key

## Tech Stack
- Vanilla HTML/CSS/JS (no build step required)
- PDF.js (cdnjs) for PDF rendering
- jsPDF (cdnjs) for PDF export
- Anthropic Claude API (claude-opus-4-5 vision)

## Cloudflare Pages Deploy
- Build command: (none)
- Output directory: /
- Branch: main
