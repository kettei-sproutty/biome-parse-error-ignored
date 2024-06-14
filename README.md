# Biome doesn't ignore parse error on ignored files

Expected:
- ignored.ts and parse-error-ignored.js are ignored by biome

Actual:
- parse-error-ignored.js contains errors