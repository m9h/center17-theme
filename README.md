# center17 (Ghost theme)

The projects.center17.org design, as a Ghost theme for center17.org. Dark, Palatino body, monospace index, red 17.

Build: `zip -r dist/center17.zip . -x 'dist/*' '.git/*' 'README.md'`, then upload in Ghost Admin → Settings → Design → Change theme → Upload, or `POST /ghost/api/admin/themes/upload/`.

Validate: `npx gscan .`
