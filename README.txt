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

Audio update:
- Fireworks have a custom soundscape with launch whistles, booms and sparkling crackles.
- The birthday song starts on the Continue tap immediately before the blossom/fireworks sequence. This is intentional: browsers block sound that tries to autoplay without a user gesture.
- The music toggle remains available to pause or resume the song.
