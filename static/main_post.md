## Sketching

Being a low-tech guy, I enjoy using simple tools and methods and
doing everything the analog way. I create sketches on a simple
B5 sketchbook with pencil, scanned and inverted before publishing.
Post processing is minimal, just a small adjustment on the
brightness curve of the image.

When I've done my first sketch into a B5 sketchbook it was
just a FOV circle on the top of the page.
The template for the circle was a lid of a yoghurt container
because it was the first thing I've found with the proper size.
As I take observation notes to a different notebook, there was
a lot of remaining space on the page. This gave me the idea to
draw a second, incomplete FOV for one more sketch.
I liked the result and I've stuck with this style.

> By the way this was [Messier 11](obs/m11-2025-06-27.md),
> the second sketch is the same object with different magnification.

I use different colors during sketching.

- blue pen for FOV and sketch notes,
- red pencil for highlights in the FOV,
- graphite pencils for most of the sketch (2H-3B), and
- a series of color pencils for colored stars and nebulae.
  
I like the idea of drawing with inverted colors but it's challenging
to find the matching color pencils, especially for yellow stars.
My current setup and the inverted result looks like
![colors](img/colors_combined.jpg)

To make a colored star brighter I've also tried to put a little gray or black
dot in the middle but it's really hard to do well.

The code of lines and points identifies the color by its
approximate RGB spectrum. This is marked on the pencils to
be able to identify in the dark:
![pencil](img/pencil.jpg)

> Note that `|||` pencil is grey instead of white. For white color I
> trivially use the ordinary graphite pencils.


## Inspiring links

I'd never started sketching without seeing the awesome work of others.
Let's name a few!

- [Richard Orr's Astronomy Drawings](https://orrastrodrawing.com) is my
  personal favorite. A huge amount of observations with interesting stories.
  So good that I'd buy a hard copy if it were available. Thank you, Richard!
- [Deep-sky Watch](https://www.deepskywatch.com/astronomy-sketches.html)
  by Michael Vlasov. Michael creates realistic and detailed drawings, it's amazing.
- [The Belt of Venus](http://perezmedia.net/beltofvenus/) by Jeremy Perez.
  He also has fantastic articles about sketching
  [techniques](https://perezmedia.net/beltofvenus/category/tools-and-techniques/).
- The album of [Carol L](https://www.cloudynights.com/gallery/member/4175-Carol%20L/)
  and the whole community on [Cloudy Nights](https://www.cloudynights.com).


## Site info

I've created this site mainly for personal use to organize my observations.
I just wanted some simple static content with easy publishing that fits my
workflow.

I decided to write [markdown](https://en.wikipedia.org/wiki/Markdown)
pages as I didn't want to use any fancy web UI to edit and publish.
Then I wrote a simple python program ([astro-gen](https://github.com/baltth/astro-gen))
to generate the site content based on [YAML](https://en.wikipedia.org/wiki/YAML)
files containing the observation data. This helps to minimize time spent with editing.

> Raw content of the YAML files are like
> ```yml
> - name: NGC 6633
>   date: 2025-08-19 23:20
>   nelm: 4.5
>   ap: 127
>   mag: 48
>   fov: 1.1
>   img: ngc-6633-20250820.jpg
>   text: |
>     This sketch was a challenge.
>     I've tried to interpret the proper relative brightness
>     of the stars but the result lacks the real shine of
>     the main ones.
> ```

I use [Github Pages](https://docs.github.com/pages) to host the site.


### About me

_Balázs Tóth -- novice in astronomy -- software architect -- 
Hungarian -- father of two -- eastern catholic -- 
playing the bass -- fishing -- happy if offline_

I'm a bit lazy in communications, but feel free to contact me
with any questions: `baltth at gmail dot com`.
Please add `[astro]` to the subject to avoid getting into spam.

