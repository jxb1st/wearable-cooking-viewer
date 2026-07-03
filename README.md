# Wearable-AI & Qualcomm Interactive Cooking — dataset viewer

Static viewer showing real samples from two egocentric instructional benchmarks:

- **Meta Wearable-AI** (ECCV 2026) — EgoLongQA (long-video MCQ), EgoConv (multi-turn
  conversational QA), EgoProactive (interrupt-vs-silent proactive decisions).
- **Qualcomm Interactive Cooking** (NeurIPS 2025, on CaptainCook4D) — live timed
  instruction + feedback streams with a 5-type mistake taxonomy (measurement /
  preparation / technique / timing / temperature) timestamped to the video.

`index.html` is self-contained (sample annotations embedded as JSON). Videos under
`videos/` are full-length, re-encoded to 480p/360p H.264 (audio stripped) to stay
under GitHub's 100 MB/file limit while remaining aligned to the annotation timestamps.

Live: https://jxb1st.github.io/wearable-cooking-viewer/
