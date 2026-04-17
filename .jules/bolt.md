## 2024-05-15 - Unoptimized Assets in Markdown-only Repos
**Learning:** Even in repositories containing purely Markdown and static documentation, large unoptimized assets (like 723KB diagram PNGs) can act as bottlenecks for repo download/checkout speed and web documentation loading times. Image quantization can reduce these by ~75% without noticeable quality loss.
**Action:** Always check `.png`, `.jpg`, and `.webp` assets in documentation-centric repositories as primary targets for performance (size) improvements using tools like `pngquant`.
