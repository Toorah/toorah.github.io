# toorah.github.io

Website for ATK Interactive's apps, served by GitHub Pages at https://toorah.github.io/
(Jekyll builds it on every push to `master`; nothing to install).

| Page | File | URL |
| --- | --- | --- |
| Home | `index.md` | / |
| Lokum | `lokum/index.md` | /lokum/ |
| Lokum privacy policy (linked from Play Console) | `lokum/privacy.md` | /lokum/privacy/ |
| Fude | `fude/index.md` | /fude/ |
| Fude privacy policy (linked from Play Console) | `fude/privacy.md` | /fude/privacy/ |

Pages are Markdown with front matter (`title`, `app`, `app_name`, `icon`, `accent`);
the shared look is `_layouts/default.html`, the site title and contact address are in
`_config.yml`. The address is never written out in this repo or the pages (crawlers
harvest both): `_config.yml` stores each half reversed and a script joins them in the
browser. Put it anywhere with `{% raw %}{% include email.html %}{% endraw %}`. A new app: copy a folder, change the front matter, add it to `index.md`.
When a privacy policy changes, update its "Effective" date. Keep the privacy URLs stable:
Play Console links to them.
