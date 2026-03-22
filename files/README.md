# Meaganne-Moussa Ali Herab — Portfolio v2

Personal portfolio with Tableau integration, built with HTML, CSS, and vanilla JavaScript.

## File structure

```
portfolio/
├── index.html       ← main page
├── css/
│   └── style.css    ← all styles (peach/orange palette)
├── js/
│   └── main.js      ← cursor, animations, nav, mobile menu
└── README.md
```

## Deploy to GitHub Pages

1. Create a repo named `MeaganneAli.github.io`
2. Upload all files keeping the folder structure above
3. Go to **Settings → Pages → Source → Deploy from branch → main**
4. Live at: `https://MeaganneAli.github.io` in ~2 minutes

## To update your Tableau embed

In `index.html`, find the `<object class="tableauViz">` block and update:
- `name` param → your viz path from Tableau Public URL
- `static_image` param → screenshot URL from Tableau

Your Tableau profile: https://public.tableau.com/app/profile/meaganne.ali/vizzes
