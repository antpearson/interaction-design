# GSAP and ScrollTrigger examples

Open **index.html** with Live Server (right-click it in VS Code → Open with Live
Server). It lists all nineteen examples, says which one to start from for what
you are trying to do, and ends with the set-up snippet and a list of the things
that usually go wrong.

Each example is one HTML file: the page, its CSS and its script, all commented.
Read it top to bottom, scroll it, change a number, scroll again.

| # | File | What it shows |
|---|------|---------------|
| 01 | `01-reveal-on-scroll.html` | Fade in when something reaches a line; stagger; scrubbed reveal |
| 02 | `02-pin-and-scrub.html` | Pin a screen-sized scene, scrub a timeline of beats |
| 03 | `03-scroll-progress-dice.html` | A marker rolling along the bottom as a whole-page progress indicator |
| 04 | `04-sticky-steps.html` | Sticky picture, scrolling text steps that change it |
| 05 | `05-pinned-title-and-counter.html` | Pinned title, depth counter, darkening background, count-up |
| 06 | `06-motion-path-timeline.html` | A route that draws itself and a marker that follows it |
| 07 | `07-horizontal-scroll.html` | A section that scrolls sideways |
| 08 | `08-deal-reveal-return.html` | A long labelled timeline: tiles dealt out, turned over, taken back |
| 09 | `09-flip-cards.html` | Tiles that flip on hover, tap and scroll |
| 10 | `10-typewriter-text.html` | Typewriter text and split-text titles |
| 11 | `11-hotspots-and-popups.html` | Clickable hotspots on a picture, animated pop-ups |
| 12 | `12-decision-branch.html` | Scroll stops until the reader chooses; two outcomes |
| 13 | `13-pick-and-build.html` | Pick from three columns, build a result, side panel |
| 14 | `14-glossary-and-tooltips.html` | Expanding glossary and inline term tooltips |
| 15 | `15-draggable-reveal.html` | Drag an object along a track to drive a timeline |
| 16 | `16-image-sequence-scrub.html` | Scrub through rendered frames on a canvas (3D without 3D code) |
| 17 | `17-scene-transitions.html` | Crossfade, background colour, sparkle burst, fade to black |
| 18 | `18-cover-slider.html` | Cover photo slider with dots and arrows |
| 19 | `19-video-scrub.html` | Scrub a video with the scrollbar |

`shared/examples.css` holds the basics every page uses. `frames/` holds 40
placeholder images for example 16; replace them with your own renders.

GSAP is loaded from a CDN, pinned to version 3.15.1. All plugins are free.
