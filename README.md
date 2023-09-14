# pokemon-parallax
Simple example of the parallax effect using Pokemon cards

## index.html
Open index.html in your browser to see the example without parallax css being applied
[index.html on GitHub Pages](https://codingLogan.github.io/pokemon-parallax/)

## parallax.html
Open parallax.html in your browser to see the example WITH parallax css being applied.
[parallax.html on GitHub Pages](https://codingLogan.github.io/pokemon-parallax/parallax.html)

## firefox-broken.html
Open this file in Firefox to see how the 3d effect doesn't work without transform-style: preserve-3d;

Notice, this page does work on Chrome and Safari just fine, but NOT Firefox

[firefox-broken.html on GitHub Pages](https://codingLogan.github.io/pokemon-parallax/firefox-broken.html)

## firefox-fixed.html
Open this file in Firefox to see how the 3d effect now works because transform-style: preserve-3d; has been applied to the groups

Now the major browsers are all working.

[firefox-fixed.html on GitHub Pages](https://codingLogan.github.io/pokemon-parallax/firefox-fixed.html)

## background-broken.html
Here you can see side effects to watch out for with setting background css on nexted 3d elements
[background-broken.html on GitHub Pages](https://codingLogan.github.io/pokemon-parallax/background-broken.html)

## Notes
The effect is based around using a few different properties of css
perspective
perspective-origin
transform: translateZ(...)
