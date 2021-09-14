# Generative & Inclusive Art in Javascript

1. Generate 100 rectangles in (Vanilla) Javascript.

As simple as a loop.

We basically have a visualisation of the function y=x, except the y axis is inverted (opposite to be precise), therefore our function is more like y=-x.

That's not very interesting, at least visually.

Before we continue, try adding some randomness to make it more visually appealing.

Try something like: `rect.setAttributeNS( null,'y',Math.random()*100+"%" );`, or, `rect.setAttributeNS( null,'style',"fill:transparent;stroke:"+ ['blue','red','yellow'][Math.round(Math.random()*2)] +";stroke-width:5;opacity:0.5" );` and see what it produces.


That's cool and all but when thinking about adding some interactivity to include external inputs in our piece. 

You can now move to the 'Interactivity' branch of this repository.

Under Linux:

```
git checkout Interactivity
```

# Art Génératif et Inclusif en Javascript

1. Générez 100 rectangles en pure (vanilla en anglais) Javascript.

Simple comme loop.

<!-- Vous pouvez maintenant vous rendre sur la branche 'Generate100Rectangles' de ce répertoire.

Sous linux:

```
git checkout Generate100Rectangles
``` -->