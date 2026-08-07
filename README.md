# dds

Small business website project hosted with GitHub Pages.

## Theme

This repository is scaffolded to use the free Jekyll theme `minimal-mistakes` via GitHub Pages `remote_theme`:

- `mmistakes/minimal-mistakes`

## Local Development

1. Install Ruby + Bundler.
2. Install dependencies:

	```bash
	bundle install
	```

3. Run the site:

	```bash
	bundle exec jekyll serve
	```

4. Open `http://127.0.0.1:4000`.

## Customize

- Site settings and theme options: `_config.yml`
- Home page layout entrypoint: `index.html` (using `layout: splash`)
- Main navigation links: `_data/navigation.yml`
- Starter About page: `about.md`
- Services page: `services.md`
- Contact page: `contact.md`
- Theme styling overrides: `assets/css/main.scss`
- Hero background asset: `assets/images/hero-bg.svg`

## Legal

- [License](LICENSE)
- [Privacy Policy](PRIVACY_POLICY.md)
- [Terms of Use](TERMS_OF_USE.md)
