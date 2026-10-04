# Video Chat AI — Aya

Aplikasi web chat dengan persona AI perempuan (Aya): chat teks + balasan suara otomatis + avatar animasi yang "berbicara". Dibuat mobile-first agar nyaman dipakai di HP Android.

## Cara pakai

1. **Dapatkan Gemini API key gratis** di https://aistudio.google.com/apikey
2. **Aktifkan GitHub Pages**: di repo ini buka *Settings → Pages → Deploy from a branch* → pilih branch `main`, folder `/ (root)` → Save. Tunggu ~1 menit, lalu buka URL yang muncul (format: `https://suburindonesia76-cyber.github.io/video-chat-ai/`).
3. Buka aplikasinya di browser HP, tekan ikon ⚙️, tempel API key, Simpan.
4. Mulai chat! Setiap balasan Aya otomatis dibacakan dengan suara. Tekan 🔊/🔇 untuk bisukan.

## Catatan

- API key hanya tersimpan di `localStorage` HP kamu, tidak dikirim ke mana pun selain Google.
- Suara memakai text-to-speech bawaan browser (gratis). Kualitas suara tergantung perangkat.
- Avatar memakai animasi CSS saat "berbicara" (pengganti file video agar repo tetap ringan).
