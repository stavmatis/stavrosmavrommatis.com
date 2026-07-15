# Portfolio concept — reference and source notes

## Visual reference

- Lafys post: https://lafys.com/posts/solv-finance-landing-page-1784119173679
- Original showcase: Bogdan / QClay
- Inspected asset: the complete 22.383-second, 2272×1440 interaction video, sampled at two frames per second and at every major scene change.
- The implementation borrows the reference’s design mechanics and pacing, not its brand, copy, or assets.

## Reused mechanics and sequence

- A large rounded website viewport floating over a static, pre-blurred image backdrop.
- A short opacity-and-transform entrance for the hero, followed by smooth native scrolling inside the framed viewport.
- Compact pill navigation, full-bleed photography, a bottom-left editorial headline, and a floating white proof/chart card.
- A looping organisation rail directly after the hero.
- The reference’s section rhythm: split introduction with paired cards, three equal proof cards, an interactive lime calculator panel, a dark two-column FAQ, full-bleed moving media, article cards, pale-lime CTA, and dark rounded footer.
- White editorial sections, dark olive contrast sections, pale aqua cards, electric-lime accents, tightly tracked sans-serif headings, and restrained micro-labels.
- A thin lime progress rail that tracks the inner desktop scroller.
- Mobile removes the nested frame and becomes a normal edge-to-edge document.

## Performance choices

- No animation or smooth-scroll library: entrance, marquee, reveal, and progress behavior use CSS plus small IntersectionObserver/requestAnimationFrame handlers.
- The full-screen backdrop is a pre-blurred 1.2 KB WebP rather than a runtime blur filter.
- The hero uses responsive 40 KB and 97 KB WebP sources with explicit dimensions and high fetch priority.
- Card previews are cropped, resized WebPs. This avoids decoding or loading the original 5.3 MB long-form email PNG during page entry.
- The full-bleed MP4 has no `src` until its section nears the viewport; it cannot compete with the hero during initial load.

## Portfolio source material

Content and evidence were adapted from the current production portfolio in the repository root and its existing assets. The concept keeps the same supported claims:

- 15+ Pyxi cultural events.
- 70 paid tickets in the first two months.
- £1,000+ revenue from the first paid events.
- 50+ attendees at the York screening with Screen Yorkshire.
- Product, marketing, CRM/email, creative, live-event, FilmPulse, dissertation, Off The Record, and MatchPoint material.

No new employment claims or unsupported metrics were added.
