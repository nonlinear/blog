# jekyll-template

<a href="https://praxis.nyc"><img src="https://praxis.nyc/assets/favicons/apple-touch-icon.png" width="60px" height="60px" /></a>

Jekyll template with some cool add-ons:
- bootstrap
- [reveal.js](https://revealjs.com/#/) slide template
- [animate.css](https://daneden.github.io/animate.css/) SASS port

> This is a generic version for the [Praxis.nyc](https://praxis.nyc/) website.

> Questions? Comments? Debugging? [Join our group on keybase](https://keybase.io/team/praxis_nyc).

### Running it locally

You need [node](https://nodejs.org/en/download/) for npm, and [jekyll](https://jekyllrb.com/docs/installation/macos/).

Clone repo, go to folder on terminal and run ` bundle exec make serve`.

When it's running, go to [https://localhost:4000](https://localhost:4000) on your browser.

### Personalizing

1. Def start with `_config.yml`
1. Change favicons
1. Design `_layouts/template.html`
1. Design `_sass/layout.scss`
1. Create new pages on `_posts`

### Troubleshooting

We're tring to fix vulnerabilities from get go, using `npm install lodash.mergewith@4.6.2 set-value@2.0.1 mixin-deep@1.3.2 lodash@4.17.12 diff@3.5.0 js-yaml@3.13.1 fstream@1.0.12 tar@2.2.2 extend@3.0.2 --save` but do try `npm audit fix` if still showing errors.
