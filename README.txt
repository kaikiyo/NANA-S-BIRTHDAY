Nana Birthday Website — centered reactions and fireworks layout fix

Upload all contents of this folder to the root of the GitHub Pages repository.
Keep index.html beside the assets folder.

Latest reaction videos:
- YES: dancing cat, cropped to the clean image area and centred.
- NO: crying banana, cropped to the clean image area and centred.

The animated canvas fireworks and Happy Birthday, Nana headline are centred
inside the full-screen overlay and wrap responsively on laptop and mobile screens.


Latest update: Background music replaced with the newest audio recording supplied on 2026-11-08. The extracted soundtrack is stored at assets/nana-new-song.mp3 and is used by the looping birthday audio player.

Cache-busting fix: the replacement track has a new filename (assets/nana-song-2026-11-08.mp3) so browsers do not reuse a previously cached song.


Update 2026-11-09:
- Added the supplied butterfly reference as two softly floating butterfly layers alongside the blossom garden. The source video is cropped to remove the phone interface and audio.
- Updated the cake styling to a strawberry-and-cream cake inspired by the supplied reference, with a wedge-shaped slice that begins attached and then lifts away.
Keep the assets folder beside index.html when deploying.

Latest reference update:
- The butterfly artwork is a clean, full-width landscape animation cropped from the supplied butterfly reference. It no longer appears in small circular thumbnails and contains no phone/social interface.
- The butterfly banner plays together with the blossom scene and fades with it.
- The cake styling is based on the supplied red strawberry cake reference, with a wedge-shaped slice that begins attached and then moves outward.
Keep assets/butterfly-collage-strip.mp4 in the assets folder.

Butterfly animation update:
- Replaced the rectangular butterfly video strip with the supplied JavaScript burst-and-float effect.
- Touching the blossom now starts the blossom bloom and generates 35 butterflies at the same time.
- Butterflies launch from the centre and fly outward on randomized paths, sizes, rotations and timings.
- The butterfly layer fades away with the blossom scene before the fireworks transition.
- A butterfly emoji fallback is included if the external butterfly artwork URLs are unavailable.

Music timing update:
- The birthday soundtrack now starts when the visitor clicks the YES / "はい、私です" button.
- Playback begins from the start of the track and continues through the reaction, blossom/butterfly scene and birthday celebration.
- The music toggle updates to Pause when playback succeeds; if the browser blocks playback, it offers the manual play control.

Mobile layout and music continuity update:
- Removed the layered 3D hanging lantern/crystal decorations on narrow screens that were rendering as long vertical trails in iPhone Safari.
- Reduced sakura particle count on mobile, simplified mobile transforms, and improved spacing for title, letters and cake.
- Countdown is repositioned below the music control and fades out after scrolling so it does not cover the letters or cake.
- Birthday soundtrack is kept playing through letter/cake interactions; if iOS Safari interrupts playback while the page remains active, the player attempts to resume unless the visitor manually paused it.
