# GAMEWAVE Music — Web/PWA Netlify Ready

Versi Web/PWA dari GameWave Music. React + Vite + TypeScript, local-first dengan IndexedDB, tanpa backend untuk V1.

## Fitur
- Home, Search, Library, Playlists, Profile
- Import multi-file MP3/M4A/AAC/WAV/FLAC/OGG/OPUS (dukungan playback mengikuti browser)
- File musik disimpan di IndexedDB browser
- Favorites, playlist, recently played
- Queue dasar, next/previous, shuffle/repeat
- Mini player dan fullscreen player
- PWA installable
- Service worker app shell
- Netlify SPA redirect sudah tersedia

## Build
npm install
npm run build

Hasil: `dist/`

## Netlify
Import repository GitHub, lalu gunakan:
- Build command: `npm run build`
- Publish directory: `dist`

Atau upload isi `dist` untuk deploy manual.

## Catatan
Netlify hanya meng-host aplikasi. Musik pribadi tidak diupload ke Netlify; musik tersimpan lokal pada browser/perangkat pengguna. Clear site data/browser dapat menghapus library lokal. Sinkronisasi akun/cloud bisa ditambahkan pada V2.
