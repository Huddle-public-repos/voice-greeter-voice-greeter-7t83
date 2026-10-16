# Build ElevenLabs text-to-speech page · prototype

A dependency-free Node server plus a single mobile-friendly page. Type a sentence, press Speak, and the server calls only ElevenLabs text-to-speech (voice JBFqnCBsd6RMkjVDRZzb, model eleven_flash_v2_5) with `ELEVENLABS_API_KEY` and returns MP3 that plays in the browser. Try it with `ELEVENLABS_API_KEY=... node server.js` and open http://localhost:3000.

**Built for:** Build a minimal web page with a text input field for sentences, a Speak button, and audio output. Use ElevenLabs text-to-speech API with voice ID JBFqnCBsd6RMkjVDRZzb and model eleven_flash_v2_5. Only use the text-to-speech endpoint, no other ElevenLabs endpoints.
(Asked by Kishore: "Huddle, build a tiny ElevenLabs text-to-speech page: type a sentence, press Speak, and hear it in a natural voice. Use voice ID JBFqnCBsd6RMkjVDRZzb and model eleven_flash_v2_5, and no other ElevenLabs endpoints.")

**Live:** https://3000-f694c117-666a-40ef-8b32-7989fdec3578.daytonaproxy01.net

**Evals:** smoke_test 1.00 · build_success 1.00
