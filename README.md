[README (2).md](https://github.com/user-attachments/files/26168822/README.2.md)
# Star Poetry

An interactive night-sky experience where hidden stars hold the words of poems. Click each star to reveal its word — collect them all to uncover the full poem.

---

## How to Play

1. Open `star-poetry.html` in any modern browser
2. Move your cursor across the night sky — hovering over a hidden star reveals a poetic hint describing its word
3. Click a star to discover its word, which floats upward before fading
4. Find all the words in the current poem to reveal the complete lines
5. Collected poems are saved to your **collection** for the duration of your session

---

## Navigation

| Button | Action |
|---|---|
| **next poem →** | Advance to the next poem and begin seeking |
| **seek again** | Appears on the final poem — resets the current poem's stars |
| **collection** | View all poems you've found so far |
| **seek** (in collection) | Return to seeking the current poem |
| **close** (in collection) | Dismiss the collection panel |

The **collection button** in the bottom-right corner shows your progress (e.g. `3 / 11`) at all times.

---

## The Poems

The experience contains 11 poems. The first is an original short poem written for this project; the remaining 10 are famous lines drawn from the public domain.

| # | Title | Author | Year |
|---|-------|--------|------|
| 1 | *Star Poetry* | original | — |
| 2 | *Ozymandias* | Percy Bysshe Shelley | 1818 |
| 3 | *The Tyger* | William Blake | 1794 |
| 4 | *Ode to a Nightingale* | John Keats | 1819 |
| 5 | *I Wandered Lonely as a Cloud* | William Wordsworth | 1807 |
| 6 | *Because I could not stop for Death* | Emily Dickinson | c. 1863 |
| 7 | *Remember* | Christina Rossetti | 1849 |
| 8 | *She Walks in Beauty* | Lord Byron | 1815 |
| 9 | *A Dream Within a Dream* | Edgar Allan Poe | 1849 |
| 10 | *Crossing the Bar* | Alfred Lord Tennyson | 1889 |
| 11 | *O Captain! My Captain!* | Walt Whitman | 1865 |
| 12 | *Invictus* | William Ernest Henley | 1875 |

Each poem uses a single iconic passage — a line or couplet — with each word hidden as a star in the sky.

---

## Technical Notes

- Single self-contained HTML file — no build step, no dependencies, no server required
- All rendering is done on an HTML5 Canvas
- Font: Cormorant Garamond (loaded from Google Fonts — requires an internet connection)
- Collection is stored in memory only and resets on page refresh
- Works on desktop and touchscreen devices

---

## Files

```
star-poetry.html    the complete experience
README.md           this file
```
