# Grow with Honey

Website for Grow with Honey: weekly one-to-one early years (EYFS) sessions in Dubai for FS1 and FS2 children.

The whole site is one file, `index.html`, with three tabs: Home, Family progress (example) and Enrol.

## Weekly wow moment

In `index.html`, find `const WOW=[` and add a new line at the top of the list:

```js
{img:'PHOTO LINK',when:'Week 10 · 4 Nov',area:'Maths',text:'What the child did',who:'FS2'},
```

The first entry shows as the "Wow moment of the week" at the top of the home page. Only post a child with the family's social media consent.

## Hosting

Served by GitHub Pages from the `main` branch (Settings → Pages → Deploy from a branch → `main` / root).
