# Supernatural Software — spntl.com

Static site hosted on Netlify.

## How to deploy (drag & drop)

1. Go to [app.netlify.com](https://app.netlify.com)
2. Drag the entire project folder onto the deploy area
3. Done — site is live

## How to add a new project page

1. Create a new folder (e.g. `syh/`)
2. Add an `index.html` inside it with your page content
3. Re-deploy by dragging the whole project folder to Netlify
4. The page will be live at `spntl.com/syh`

## Contact form

The contact form uses [Netlify Forms](https://docs.netlify.com/forms/setup/).  
Submissions appear in the Netlify dashboard under **Forms**.  
You'll receive email notifications (configure in Netlify → Forms → Notifications).

## Site structure

```
spntl.com/
├── index.html        ← homepage
├── 404.html          ← custom 404 page
├── _redirects        ← Netlify redirect rules
├── images/           ← shared images
└── syh/              ← example: project page
    └── index.html
```
