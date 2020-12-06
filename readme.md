# Pilot Instructor Webpage

Trying out some ideas for a static web page for my brother. I wanted to use [Yuan Chen's single div clouds](https://codepen.io/yuanchuan/pen/f70a1f9435dc90197b253b26b4d69d42) for a nice visual gimmick. For the color scheme I was thinking of something based off atmospheric scattering during sunrise.

The clouds are inspired by this cool [article](https://css-tricks.com/drawing-realistic-clouds-with-svg-and-css/) by Beau Jackson. Probably inconsiderately processor intensive for visitors, but still cool.

## todo

 - Add more clouds, infront and behind the main logo so the logo plunges through when you scroll....

 - Make the clouds move? Maybe drift horizontally slowly? A bit of vertical parallax when scrolling?

 - I need to trace some more planes, instead of re-using the piper cub...

 - Align the plane tire below the ground gradient- it looks like it's floating...

 - I need to keep the text from going into different atmospheric color bands.
   - I could do this by making a gradient div for each band and stacking them. then they could grow with content independently and the appropriate foreground color could be chosen for them.
   - Unfortunately this precludes the ability to programatically alter bands by altitude as you scroll.

Thinking about simulating atmospheric scattering by altitude as you scroll; as if the pane is taking off...
 - https://www.scratchapixel.com/lessons/procedural-generation-virtual-worlds/simulating-sky