# portfolio

My personal site. Dark, terminal-y theme because I spend most of my day in one anyway.

Plain HTML/CSS, no framework, no build step — just open a file and it works.

## Structure

```
index.html         home
experience.html    work history
projects.html      side projects
education.html     degrees, certs, publications
contact.html       how to reach me
assets/css/        the one stylesheet everything shares
```

Each page has its own accent color and background pattern (blue log lines for experience,
a blueprint grid for projects, etc.) but shares the same layout and CSS file.

## Running it locally

No build step, so just open `index.html` in a browser, or serve it if you want relative
links to behave exactly like they will on GitHub Pages:

```bash
python -m http.server 5500
```

then go to http://localhost:5500

## Deploying

Pushed to GitHub, Pages source set to `master` / root. That's it.

## To do

- [ ] Swap in real project screenshots instead of just text
- [ ] Maybe add a resume PDF download link
