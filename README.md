# BruLive (Brutal Live)

Aplikasi Android buat streamer TikTok Live yang pengen bikin live-nya lebih interaktif — mulai dari ngubah gift/komen/follow jadi aksi di Minecraft Bedrock, sampai nge-live langsung dari HP pakai Stream Key, lengkap dengan panel pemantau penonton & komen real-time.

Semuanya jalan 100% di HP, gak butuh PC/laptop.

> **Catatan:** BruLive **bukan** "BedrockLive" (project berbeda, berjalan via local server + PC). BruLive adalah aplikasi Android mandiri yang punya Mode Game dan Mode Stream sendiri di luar Minecraft, bukan sekadar relay event.

---

## Daftar Isi

- [Fitur Utama](#fitur-utama)
- [Cara Install](#cara-install)
- [Login & Akun](#login--akun)
- [Mode Game Minecraft (TNT Coin & Sand Sweep)](#mode-game-minecraft-tnt-coin--sand-sweep)
- [Mode Game (Panjat Bukit)](#mode-game-panjat-bukit)
- [Mode Stream](#mode-stream)
- [Toko & Langganan](#toko--langganan)
- [Fitur Tambahan](#fitur-tambahan)
- [FAQ / Troubleshooting](#faq--troubleshooting)

---

## Fitur Utama

| Fitur | Keterangan |
|---|---|
| **Relay TikTok → Minecraft** | Gift, like, follow, member join, dan chat dari TikTok Live langsung memicu aksi di Minecraft Bedrock |
| **TNT Coin** | Addon Minecraft pihak ketiga (open-source, MIT License) - TNT Challenge klasik, gift = TNT muncul |
| **Sand Sweep** | Addon Minecraft buatan sendiri - mode "bersihin platform dari pasir", sistem Event Actions mirip TNT Coin (bisa custom aksi per gift/like/follow/member/chat) |
| **Mode Game (Panjat Bukit)** | Mini-game 2D di dalam app sendiri - streamer panjat bukit, penonton ganggu/bantu lewat gift |
| **Mode Stream** | Live langsung ke TikTok dari BruLive pakai Stream Key, mode Kamera atau Game (screen capture) |
| **Panel Live (floating)** | Bundaran jumlah penonton, komen, follow, gift - update real-time, bisa digeser bebas di layar |
| **Text-to-Speech (TTS)** | Baca komentar penonton otomatis |
| **Public Chat** | Chat antar pengguna BruLive (khusus VIP/dev) |
| **Toko Script** | Beli/unlock mode tambahan |
| **Sistem Langganan** | Member & VIP, paket Mingguan/Bulanan/Tahunan/Permanen |
| **Panel Admin (dev)** | Kelola langganan user, tambah user baru |

---

## Cara Install

1. Download file `.apk` BruLive, install di HP Android.
2. Buka app, **login** pakai akun yang udah dikasih dev (username & password).
3. Kalau belum punya akun, hubungi admin/dev buat didaftarin.

---

## Login & Akun

Ada 2 role utama:

- **Member** - akses dasar: TNT Coin, TTS, fitur umum.
- **VIP** - semua akses Member + Mode Game, Mode Stream, Public Chat, dan mode-mode premium lain.
- **Dev** - akses penuh + panel admin (kelola langganan, tambah user).

Status langganan (expired/aktif) kelihatan otomatis tiap buka app.

---

## Mode Game Minecraft (TNT Coin & Sand Sweep)

**Cara pakai:**
1. Buka Minecraft Bedrock, aktifkan addon **TNT Coin** atau **Sand Sweep** di world kamu.
2. Buka BruLive, masukin **username TikTok** kamu di kolom Connect, tekan **Connect**.
3. Masukin IP/port yang ditampilkan BruLive ke Minecraft lewat `/connect <ip>:<port>` (atau menu Settings dunia, tergantung versi).
4. Setelah connect, gift/like/follow/chat dari TikTok otomatis memicu aksi di game.

**Konfigurasi aksi (Sand Sweep):**
- Klik kanan item **"Sand Sweep Settings"** (shovel) di game.
- Masuk ke **Event Actions** → pilih kategori (Gift / Like / Member / Follow / Chat).
- Tambah aksi: Tambah Pasir, Tambah Baris Pasir, Spawn TNT, Play Sound, atau Screen Title.
- Satu event bisa punya banyak aksi ditumpuk, dan Like Actions pakai sistem threshold (misal: tiap 100 like, jalanin aksi tertentu).

---

## Mode Game (Panjat Bukit)

Mini-game 2D interaktif, berjalan langsung di dalam BruLive (bukan Minecraft).

**Cara pakai:**
1. Buka drawer (hamburger ☰) → **Mode Game** *(khusus VIP/dev)*.
2. Pilih game **Panjat Bukit** → tekan **Main**.
3. Streamer tap layar buat lompat menghindari rintangan.
4. Penonton pengaruhin lewat gift (jatuhin batu/tong/bongkahan sesuai harga gift) dan follow (kasih perisai).

---

## Mode Stream

Nge-live langsung ke TikTok dari BruLive sendiri, tanpa buka app TikTok buat broadcast (TikTok tetap dipakai buat dapetin Stream Key & klik Go Live).

**Syarat:** Akun TikTok kamu harus eligible LIVE Studio (minimal 1000 followers) buat dapat Server URL + Stream Key dari TikTok.

**Cara pakai:**
1. Buka drawer → **Mode Stream** *(khusus VIP/dev)*.
2. Pilih mode:
   - **📷 Kamera** - live pakai kamera depan/belakang HP.
   - **🎮 Game (Layar)** - live pakai screen capture (buat main game lain sambil di-live-in).
3. Isi:
   - **Server URL** & **Stream Key** - didapat dari TikTok (Creator Tools → LIVE Center → LIVE via PC/software pihak ketiga).
   - **Username TikTok** - buat nyalain pemantauan penonton/komen otomatis.
4. Tekan **Mulai Live**.
5. **Wajib:** buka TikTok, cek preview udah masuk, lalu **klik "Go Live"** di TikTok - ini langkah manual yang gak bisa dilewatin (aturan TikTok, bukan soal BruLive).
6. Panel bundaran (penonton/komen/follow/gift) otomatis muncul dan bisa digeser ke mana aja di layar. Angka dibatasi tampil maksimal **99+**.

---

## Toko & Langganan

- Buka tab **Toko** buat lihat mode/addon yang bisa dibeli (misal Sand Sweep).
- Harga langganan (Member / VIP):

| Paket | Member | VIP |
|---|---|---|
| Mingguan (7 hari) | Rp 10.000 | Rp 10.000 |
| Bulanan (30 hari) | Rp 25.000 | Rp 30.000 |
| Tahunan (365 hari) | Rp 100.000 | Rp 150.000 |
| Permanen | Rp 1.500.000 | Rp 2.500.000 |

---

## Fitur Tambahan

- **TTS (Text-to-Speech)** - baca komentar penonton otomatis, nyala/mati dari toggle di app.
- **Public Chat** - ngobrol sama pengguna BruLive lain (drawer → Public Chat, khusus VIP/dev).
- **Riwayat Aktivitas** - log histori pemakaian (drawer → Riwayat Aktivitas).
- **Panel Admin (dev only)** - Kelola Langganan (extend/hapus user) dan Tambah User baru.

---

## FAQ / Troubleshooting

**Q: Udah push Stream Key tapi TikTok gak live?**
A: Push Stream Key cuma bikin preview. Harus **klik Go Live manual** di app TikTok setelah itu.

**Q: Mic mati pas pindah ke app lain waktu Mode Game (Layar)?**
A: Pastikan izin mic & "tampil di atas app lain" udah diizinkan. Update ke versi terbaru BruLive kalau masih kejadian - ini sudah diperbaiki lewat foreground service khusus.

**Q: Panel penonton/komen di Mode Stream kosong?**
A: Pastikan **Username TikTok** di Mode Stream udah diisi dan benar (tanpa `@`), dan relay-nya berhasil connect ke live TikTok kamu.

**Q: Gak bisa akses Mode Game / Mode Stream?**
A: Dua fitur itu khusus role **VIP** atau **dev**. Upgrade langganan di Toko kalau masih Member.

---

*BruLive (Brutal Live) - dibuat buat streamer yang pengen live-nya beda dari yang lain.*
