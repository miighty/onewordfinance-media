# Round 2 voice audition (25 Nov 2026, Europe/London)

Reference: Instagram reel https://www.instagram.com/reel/DfvjfxvR27o/ by Gourge Altawil / askgeorge.ai.
Saved on the box at `/workspace/owf-build/voices/reference/` (mp4, m4a, 16k wav, transcript, analysis).

**Reference voice, one line:** a young-adult American male, bright mid-tenor (~154 Hz median, wide 116–225 Hz intonation), speaking very fast at about 202 words/min with short, even pauses — almost certainly high-quality TTS, not a raw human take.

The reel voice was **not cloned**. Samples were designed from that profile (gender, accent, pitch, pace, energy) only. Production default remains `qwen3:ryan`.

Same Capita script as round 1. Where a sample was slower than the reel, a pitch-preserving `atempo` copy was used for the shortlist (and for video 01).

Scores use UTMOS 2.2 (naturalness, higher is better) and librosa pyin F0, the same method as the reference (median 153.6 Hz overall, 148 Hz in the mid section).

## Shortlist (ranked by closeness to the reference, then naturalness)

1. **qwen3vd_us_mid_male** — Qwen3 VoiceDesign, US mid male. F0 147 Hz (closest US match), UTMOS 4.40. Paced 16.0s → 12.2s. Audio + Capita video in this folder.
2. **chatterbox_full_exag070** — Chatterbox (full, built-in default, exaggeration 0.70, no reference clip). F0 141 Hz, UTMOS 4.40, already 12.6s. Audio + Capita video.
3. **kokoro_am_fenrir** — Kokoro US male Fenrir at speed 1.20. F0 142 Hz, UTMOS 4.48 (highest of the close-pitch set), already 12.4s.
4. **qwen3vd_gb_young_explainer** — Qwen3 VoiceDesign, modern British young male. F0 164 Hz, UTMOS 4.20. Closest high-side pitch if the reel were slightly British; paced to 12.2s.
5. **qwen3vd_us_down_to_earth** — Qwen3 VoiceDesign, US down-to-earth mid-tenor. F0 130 Hz (a little darker), UTMOS 4.33. Paced to 12.2s.
6. **chatterbox_full_exag050** — Chatterbox full, exaggeration 0.50. F0 132 Hz, UTMOS 4.41. Paced to 12.2s.

Ryan (current default) scored UTMOS 3.57 and F0 208 Hz at 16.7s — useful as a baseline, not a match. It was not changed.

All 19 raw samples, including Ryan, are under `all/`.

## Paid options (no sign-up, no spend, no cloned demos)

Per ~16s One Word Finance slot (~320 characters / ~50–55 words). Prices checked 25 Nov 2026.

- **ElevenLabs (best paid bet):** closest stock voices are **Adam** (bright tenor, pitch match) and **Liam** (young American, reels/shorts; Default voices expire 31 Dec 2026, suggested Infinity replacement **Lawrence – Bright and Informative**). Also try Will → Warren, Chris → Caleb. API v3/v4 ≈ **$0.026** per 16s ($0.08/1k chars, or ~$0.021 at $0.08/min). Turbo/Flash ≈ **$0.013**. Commercial licence on paid plans (Starter $6/mo+). Free plan is non-commercial.
- **Cartesia Sonic 3.6:** try **Daniel**, **Jameson**, or **Allen – Modern Voice**. About **$0.013–$0.016** per 16s on Startup/Pro credits (1 credit/character). Commercial on Pro+.
- **OpenAI:** try **ash**, **echo**, or **verse**. gpt-4o-mini-tts ≈ **$0.004** per 16s (OpenAI estimate ~$0.015/min) but **shuts down 6 Jan 2027** with tts-1 / tts-1-hd. Not a long-term option.
- **Hume Octave:** shut down 13 Nov 2026. Not an option.
