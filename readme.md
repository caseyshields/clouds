# Pilot Instructor Webpage

Trying out some ideas for a static web page for my brother. I wanted to use [Yuan Chen's single div clouds](https://codepen.io/yuanchuan/pen/f70a1f9435dc90197b253b26b4d69d42) for a nice visual gimmick. For the color scheme I was thinking of something based off atmospheric scattering during sunrise.

The clouds are inspired by this cool [article](https://css-tricks.com/drawing-realistic-clouds-with-svg-and-css/) by Beau Jackson. Probably inconsiderately processor intensive for visitors, but still cool. https://www.nephele.cloud/

The neat 3d text was from Sarah Fossheim's [article](https://css-tricks.com/creating-playful-effects-with-css-text-shadows/).



## todo

 - Add more clouds, infront and behind the main logo so the logo plunges through when you scroll....

 - use a radial gradient for a bit more natural appearance?

 - Make the clouds move? Maybe drift horizontally slowly? A bit of vertical parallax when scrolling?

 - I need to trace some more planes, instead of re-using the piper cub...
   - Piper Cub PA28-181 Archer 
   - Piper Cub PA-44 Seminole
   - Cessna 172 S Model Skyhawk 

 - Align the plane tire below the ground gradient- it looks like it's floating...

 - I need to keep the text from going into different atmospheric color bands.
   - I could do this by making a gradient div for each band and stacking them. then they could grow with content independently and the appropriate foreground color could be chosen for them.
   - Unfortunately this precludes the ability to programatically alter bands by altitude as you scroll.

Thinking about simulating atmospheric scattering by altitude as you scroll; as if the pane is taking off...
 - https://www.scratchapixel.com/lessons/procedural-generation-virtual-worlds/simulating-sky

 https://www.faa.gov/licenses_certificates/

  - this kind of thing might be good for the mission quote;
    - https://css-tricks.com/using-css-to-set-text-inside-a-circle/
    - https://css-tricks.com/snippets/svg/curved-text-along-path/

  - here's an approach for the map;
    - https://codepen.io/jakobfuchs/pen/DyAto
    - this is only for switzerland, but worth looking at the api;
      - https://codepen.io/cedricmoullet/pen/AwuIK
      - https://www.swisstopo.admin.ch/en/home.html