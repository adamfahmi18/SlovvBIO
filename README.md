# Slovv Coffee Links

Website statis Slovv Coffee yang siap dideploy ke Vercel.

## Deploy dari GitHub Codespaces

1. Buka repository GitHub di Codespaces.
2. Letakkan seluruh isi folder ini di root repository.
3. Commit dan push:

   ```bash
   git add .
   git commit -m "Add Slovv Coffee website"
   git push
   ```

4. Deploy melalui Vercel CLI:

   ```bash
   npm install -g vercel
   vercel login
   vercel link
   vercel --prod
   ```

Alternatifnya, impor repository GitHub lewat dashboard Vercel. Vercel akan membaca `vercel.json` dan memublikasikan folder `dist` secara otomatis.

## Struktur

- `dist/index.html` — halaman website
- `dist/assets/` — logo dan gambar menu
- `vercel.json` — konfigurasi Vercel
