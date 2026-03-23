# ashutoshjha3103.github.io

Personal site built with [Jekyll](https://jekyllrb.com/) and the [Minima](https://github.com/jekyll/minima) theme, deployed with [GitHub Pages](https://pages.github.com/).

## Local preview

With Ruby and Bundler:

```bash
bundle install
bundle exec jekyll serve
```

Then open `http://127.0.0.1:4000`. The same build runs in the repository’s GitHub Actions workflow on push to `main`.

## Updating the CV

Replace the file at **`assets/cv.pdf`** with your latest CV (keep the same filename), commit, and push. The **Download CV (PDF)** button on the About page points to that path.

## Profile photo

Add your headshot as **`assets/profile.jpg`** (square JPEG or PNG renamed to `.jpg` if needed). The home page hero expects this path.

## Email (anti-scraping)

The contact page does **not** embed your address as plain text. Instead, edit **`_data/contact.yml`** and set `email_char_codes` to the UTF-8 byte values of your email:

```bash
python3 -c "print(list('you@yourdomain.com'.encode()))"
```

Paste the printed list into `email_char_codes`. Visitors click **Reveal email address**; the browser assembles the string and sets `mailto:`. This deters simple harvesters but is **not** a cryptographic guarantee—determined bots can still recover the address from the numbers.

## Social / SEO preview image

Replace **`assets/og-image.png`** (recommended **1200×630** px) if you want a custom image when links to the site are shared.

## Custom styles

Global styles and dark-mode rules live in **`_sass/custom.scss`**, included from **`assets/main.scss`**.
