# ashutoshjha3103.github.io

Personal site built with [Jekyll](https://jekyllrb.com/) and the [Minima](https://github.com/jekyll/minima) theme, deployed with [GitHub Pages](https://pages.github.com/).

## Email (anti-scraping)

The contact page does **not** embed the address as plain text. Instead, need to edit **`_data/contact.yml`** and set `email_char_codes` to the UTF-8 byte values of the email:

```bash
python3 -c "print(list('you@yourdomain.com'.encode()))"
```

Need to paste the printed list into `email_char_codes`.