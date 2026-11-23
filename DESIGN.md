# VaniGuard visual direction

## Reference

- Reference: [Whoscall English homepage](https://web.whoscall.com/en)
- Reviewed: 2026-11-23
- Source file: `C:/Users/Sanu/Downloads/web.whoscall.com_en.2026-11-23T10_05_40.755Z.json` (page markdown and metadata; no screenshot or stylesheet data).
- The page capture shows a confidence-led hero, a prominent download/demo action, a short safety promise, and feature-led sections for protection, detection, and community. It introduces the brand with “Confidence Every Connection” and follows with “Smarter connections made safe and simple, every time.”
- Capture limitation: exact page pixels, CSS values, and interaction behavior are not present in the supplied JSON. The implementation adapts its content hierarchy and broad visual tone; it does not claim pixel-level matching.

## Adaptation for VaniGuard

- Keep VaniGuard’s own identity. Use warm ivory as the canvas, forest green for primary actions, and leaf green for safety emphasis; use amber and coral only for warning states.
- Put one confident promise and a direct demo action above the fold, with a floating 3D phone, safety alert, and draggable acoustic sphere as the memorable visual.
- Tell the story before the product controls: explain pressure patterns, show three feature cards, and introduce the three-step response.
- Keep the scenario controls, phone preview, risk telemetry, guardian preview, and emergency action in a dedicated interactive demo section.
- Close with a safety reminder and a direct helpline action.
- Keep simulation status visible. The concept does not capture real calls or send alerts.

## Type and layout

- Display face: Fraunces for the headline and small section titles; DM Sans for interface copy; DM Mono for telemetry labels.
- Desktop page: slim navigation, large two-column hero, three-part feature ribbon, scam story, three feature cards, response steps, then the call demo and closing action.
- Small screens: stack the hero, cards, and demo panels; keep scenario controls ahead of supporting content.
- Motion: pointer-driven 3D rotation and restrained hover transitions. Respect `prefers-reduced-motion`.
