# Hanrong Li — Academic Homepage

This site uses the original RayeRen/acad-homepage.github.io Jekyll template and preserves its MIT license and acknowledgements.

## Content

- `_config.yml`: name, affiliation, email, portrait path, GitHub username and repository.
- `_pages/about.md`: introduction, research interests, manuscript, awards and education.
- `_data/navigation.yml`: navigation entries.
- `images/hanrong-li.jpg`: the supplied profile photo, displayed with CSS cropping.
- `assets/css/main.scss`: original template styling plus a small personalization block.

Publications displays only: A paper submitted to NAACL, under review. Keep manuscript titles, figures, technical descriptions, and links out of the public source and site during anonymous review.

## GitHub Pages

Fork the upstream repository into the authenticated owner's account. Before publication, set `repository` in `_config.yml` to the actual `owner/repository` and `author.github` to the authenticated username.

For a user homepage, use the repository name `OWNER.github.io`. For a project homepage, set `url` to `https://OWNER.github.io` and `baseurl` to `/REPOSITORY`; relative_url filters are used for the key assets and framework links.

Use GitHub Pages' native Jekyll branch deployment (main / root). Do not upload `_site`, `.openai`, or local caches as source. The original citation crawler has been removed because no verified Scholar profile was supplied.

## Local verification

With Jekyll and the declared plugins installed:

```sh
JEKYLL_NO_BUNDLER_REQUIRE=true jekyll build
```

Alternatively follow the upstream README to install the full GitHub Pages bundle. The site was verified with Jekyll 4.3.2, Kramdown, and the configured plugins. Native GitHub Pages deployment must still be checked after account connection and fork.

