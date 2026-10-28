# Hanrong Li — Academic Homepage

This site uses the original RayeRen/acad-homepage.github.io Jekyll template and preserves its MIT license and acknowledgements.

## Content

- `_config.yml`: name, affiliation, email, portrait path, GitHub username and repository.
- `_pages/about.md`: introduction, research interests, manuscript, awards and education.
- `_data/navigation.yml`: navigation entries.
- `images/hanrong-li.jpg`: the supplied profile photo, displayed with CSS cropping.
- `images/taskgraph-rag-overview.png`: Figure 2 extracted from the supplied manuscript.
- `assets/css/main.scss`: original template styling plus a small personalization block.

The manuscript is labeled **NAACL · Under Review**, according to the owner's instruction. The uploaded anonymous manuscript and revision notes are not included or linked, and no author order has been inferred. The manuscript's title and framework can be updated in `_pages/about.md`. The CV PDF is not published; education and honors were transcribed from it.

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
