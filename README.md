# Pasar Hanakau — domain verification

Repository ini digunakan untuk domain utama `https://berniaja5036-blip.github.io/` untuk keperluan Android Trusted Web Activity (TWA).

## Aktifkan GitHub Pages

1. Buka **Settings → Pages** pada repositori ini.
2. Pada **Build and deployment**, pilih **Deploy from a branch**.
3. Pilih branch **main** dan folder **/(root)**, lalu **Save**.
4. Tunggu sampai GitHub Pages menerbitkan situs. Domain yang diharapkan adalah `https://berniaja5036-blip.github.io/`.

Berkas Digital Asset Links nantinya harus tersedia persis pada:

`https://berniaja5036-blip.github.io/.well-known/assetlinks.json`

## Penting

Jangan membuat `assetlinks.json` dengan sidik jari sertifikat contoh atau placeholder. Isinya harus memakai SHA-256 fingerprint dari keystore rilis permanen aplikasi `id.pasarhanakau.mobile`. Keystore dan password jangan pernah dimasukkan ke repositori publik atau dikirim melalui chat.

Petunjuk pembuatan keystore dan pengaturan GitHub Secrets ada di repositori aplikasi, pada `android/RELEASE-KEY-SETUP.md`.
