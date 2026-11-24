# Matrix Bouquet

A bouquet that grows out of glyphs. Everything on screen (petals, stems, leaves, vases, bees, the garden) is built from colored numbers, symbols and katakana that keep flickering, like Matrix rain, on a black sky full of stars.

## What happens

1. Characters pour down from the top of the screen like water. The first thing they build is a single flower standing on a little mound of moss.
2. The bouquet grows over 10 steps, up to 35 flowers: roses, peonies, ranunculus, lilies, orchids, sunflowers, hydrangeas, carnations, cosmos, daisies and tulips. Its container changes at every step, from a paper wrapper through a series of soft pastel vases. The whole bouquet slowly spins and tilts.
3. When it's fully grown, the bouquet stops and asks you to click it.
4. When you click, it drifts apart and turns into a large garden landscape. There are rolling hills, a pond with lotus flowers and lily pads, cherry blossom trees, a stepping-stone path, rows of lavender and fireflies.
5. Click any flower to zoom in from above. Each flower has 1 to 5 honey bees, more on bigger flowers, and each bee is doing something different. Click again or press Esc to go back to the garden.

Reloading the page starts everything over.

## Run it

It's a single `index.html` with no dependencies.

```
python -m http.server 8080
```

Then open http://localhost:8080. On Windows without Python, you can run the included PowerShell server instead:

```
powershell -ExecutionPolicy Bypass -File serve.ps1
```

## Controls

| Key | Action |
|---|---|
| Space | Pause |
| N / → | Skip ahead to the next step |
| Click | Release the bouquet, or zoom into a flower |
| Esc | Leave the close-up |
