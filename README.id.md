<h1 align="center">AI Visual Prompt Cookbook</h1>

<p align="center">
  <img src="assets/hero-collage.jpg" alt="AI Visual Prompt Cookbook showcase">
</p>

<p align="center">
  <a href="README.md">English</a> |
  <a href="README.zh-CN.md">简体中文</a> |
  <a href="README.zh-TW.md">繁體中文</a> |
  <a href="README.ja.md">日本語</a> |
  <a href="README.ko.md">한국어</a> |
  Bahasa Indonesia
</p>

<p align="center">
  <img alt="Styles" src="https://img.shields.io/badge/styles-38-ff5a7a?style=flat-square">
  <img alt="Previews" src="https://img.shields.io/badge/previews-76-4cc9f0?style=flat-square">
  <img alt="Format" src="https://img.shields.io/badge/format-style.json-111111?style=flat-square">
  <img alt="Languages" src="https://img.shields.io/badge/languages-6-f7b801?style=flat-square">
</p>

<p align="center">
  <strong>Salin satu JSON, dapatkan satu gaya.</strong> Masukkan <code>style.json</code> ke ChatGPT, Claude, Nano Banana Pro, atau workflow gambar berbasis LLM lain. Ganti variabelnya, pertahankan sistem visualnya.
</p>

<p align="center">
  Ini adalah pustaka gaya prompt visual siap pakai untuk generasi gambar AI. Setiap gaya disusun sebagai <code>style.json</code> yang mudah digunakan ulang, lengkap dengan preview landscape dan portrait.
</p>

<p align="center">
  Curated by <a href="https://x.com/VigoCreativeAI">@VigoCreativeAI</a>, structured with assistance from OpenAI Codex. Star repo ini untuk mengikuti rilis gaya baru.
</p>

## Tautan Cepat

| Kategori | Cocok untuk | Mulai dari |
| --- | --- | --- |
| Foto + Doodle | Foto sosial, adegan lifestyle, overlay stiker yang playful | [Playful Mascot Doodle Snapshot](styles/playful-mascot-doodle-snapshot-style), [Subway Doodle Photo Hybrid](styles/subway-doodle-photo-hybrid-style) |
| Zine + Kolase | Poster fashion, visual musik, layout editorial maksimalis | [K-pop Apocalypse Ransom Zine](styles/k-pop-apocalypse-ransom-zine-style), [Y2K Grunge Hip-hop Cutout Poster](styles/y2k-grunge-hiphop-cutout-poster-style) |
| Poster Tipografi | Headline besar, grafik kampanye yang keras, visual impact | [Impact Burst Halftone Comic Poster](styles/impact-burst-halftone-comic-poster-style), [Neon Kinetic Typographic Poster](styles/neon-kinetic-typographic-poster-style) |
| Travel + Kota | Poster destinasi, scene jalanan, diary visual perkotaan | [Tokyo Kawaii Travel Collage Poster](styles/tokyo-kawaii-travel-collage-poster-style), [Urban Transit Doodle Diary](styles/urban-transit-doodle-diary-style) |
| Editorial + Minimal | Komposisi bersih, layout terstruktur, arahan visual yang lebih tenang | [Soft Analog Future Editorial Poster](styles/soft-analog-future-editorial-poster-style), [Folded Diamond Perspective Type Poster](styles/folded-diamond-perspective-type-poster-style) |

## Kenapa Proyek Ini Ada

Banyak prompt gambar AI hanya berupa teks sekali pakai: sulit digunakan ulang, sulit dibandingkan, dan sulit diiterasi secara stabil. Repo ini memakai pendekatan berbeda: setiap gaya visual dipecah menjadi `style.json` yang terstruktur. Saat subjek berubah, struktur visualnya tetap konsisten.

## Mulai Cepat

1. Jelajahi [Gaya Unggulan](#gaya-unggulan), [Tautan Cepat](#tautan-cepat), atau [Indeks Gaya](#indeks-gaya).
2. Buka folder gaya yang kamu suka, lalu salin `style.json`.
3. Tempel seluruh JSON ke ChatGPT, Claude, Nano Banana Pro, atau workflow gambar berbasis LLM lain.
4. Isi nilai untuk variabel yang dideklarasikan di `environment_variables`, atau edit salah satu case di `examples[*].values`.
5. Buat prompt gambar final, lalu kirim ke model gambar pilihanmu.

Contoh instruksi:

```text
Gunakan style.json ini sebagai gaya visual yang terkunci.
Gunakan nilai variabel ini:
SUBJECT = fotografer produk streetwear
LOCATION = gang neon saat hujan
MAIN_TEXT = NIGHT DROP
ASPECT_RATIO = 16:9
```

## Copy Prompt Library

Ingin mencoba versi singkat dulu? Buka [Copy Prompt Library](docs/copy-prompts/README.md) untuk prompt siap salin per gaya. Sistem gaya lengkap yang reusable tetap berada di setiap `style.json`.

## Gaya Unggulan

Enam sistem visual ini menunjukkan rentang gaya dalam pustaka. Setiap gaya berisi satu JSON dan dua gambar preview.

<table>
<tr>
<td width="33%" valign="top">
<a href="styles/mono-noir-type-portrait-poster-style"><img src="styles/mono-noir-type-portrait-poster-style/preview-16x9.jpg" alt="Mono Noir Type Portrait Poster Style preview"></a>
<h3>Mono Noir Type Portrait Poster Style</h3>
<p>Gaya poster potret editorial hitam-putih dengan subjek manusia close-up kontras tinggi, headline lowercase neo-grotesque raksasa, kata pertama dalam label putih, ruang negatif arang, dan pencahayaan noir yang tegas.</p>
<p><a href="styles/mono-noir-type-portrait-poster-style/style.json"><strong>Buka style.json</strong></a> · <a href="docs/copy-prompts/mono-noir-type-portrait-poster-style.md">Copy Prompt</a> · <a href="styles/mono-noir-type-portrait-poster-style">Folder</a></p>
</td>
<td width="33%" valign="top">
<a href="styles/bold-block-mascot-poster-style"><img src="styles/bold-block-mascot-poster-style/preview-16x9.jpg" alt="Bold Block Mascot Poster Style preview"></a>
<h3>Bold Block Mascot Poster Style</h3>
<p>Gaya poster maskot flat yang padat dengan tipografi blok hitam raksasa, figur stiker putih, outline kartun tebal, panel diagonal lemon atau cyan/mint, label kartu portofolio ringkas, aksen merah kecil, dan permukaan cetak off-white yang bersih.</p>
<p><a href="styles/bold-block-mascot-poster-style/style.json"><strong>Buka style.json</strong></a> · <a href="docs/copy-prompts/bold-block-mascot-poster-style.md">Copy Prompt</a> · <a href="styles/bold-block-mascot-poster-style">Folder</a></p>
</td>
<td width="33%" valign="top">
<a href="styles/blue-hud-macro-product-poster"><img src="styles/blue-hud-macro-product-poster/preview-16x9.jpg" alt="Blue HUD Macro Creator Tech Poster preview"></a>
<h3>Blue HUD Macro Creator Tech Poster</h3>
<p>Gaya poster peluncuran creator-tech biru dengan hero hardware makro 3D, sarung tangan rib besar, panel kaca HUD sian elektrik, tipografi putih kondens besar, lapisan kartu fitur padat, dan satu badge performa emas hangat.</p>
<p><a href="styles/blue-hud-macro-product-poster/style.json"><strong>Buka style.json</strong></a> · <a href="docs/copy-prompts/blue-hud-macro-product-poster.md">Copy Prompt</a> · <a href="styles/blue-hud-macro-product-poster">Folder</a></p>
</td>
</tr>
<tr>
<td width="33%" valign="top">
<a href="styles/warm-fisheye-product-impact-ad-style"><img src="styles/warm-fisheye-product-impact-ad-style/preview-16x9.jpg" alt="Warm Fisheye Product Impact Ad preview"></a>
<h3>Warm Fisheye Product Impact Ad</h3>
<p>Gaya iklan produk social-commerce Tiongkok yang padat dengan terowongan produk makro fisheye, produk hero terpotong dekat lensa, judul Mandarin putih besar dan miring, cahaya caramel-brown hangat, tab callout biru, strip produk bawah, dan tekstur glossy.</p>
<p><a href="styles/warm-fisheye-product-impact-ad-style/style.json"><strong>Buka style.json</strong></a> · <a href="docs/copy-prompts/warm-fisheye-product-impact-ad-style.md">Copy Prompt</a> · <a href="styles/warm-fisheye-product-impact-ad-style">Folder</a></p>
</td>
<td width="33%" valign="top">
<a href="styles/olive-scribble-sports-poster-style"><img src="styles/olive-scribble-sports-poster-style/preview-16x9.jpg" alt="Olive Scribble Sports Poster preview"></a>
<h3>Olive Scribble Sports Poster</h3>
<p>Gaya poster olahraga handmade yang kinetik dengan kertas off-white, blok olive tidak beraturan, figur aksi diagonal berukuran besar, kontur tinta hitam kasar, lengkung gerak marker merah, sapuan dry-brush hijau kekuningan, dan tekstur screenprint.</p>
<p><a href="styles/olive-scribble-sports-poster-style/style.json"><strong>Buka style.json</strong></a> · <a href="docs/copy-prompts/olive-scribble-sports-poster-style.md">Copy Prompt</a> · <a href="styles/olive-scribble-sports-poster-style">Folder</a></p>
</td>
<td width="33%" valign="top">
<a href="styles/bold-anime-reaction-thumbnail-style"><img src="styles/bold-anime-reaction-thumbnail-style/preview-16x9.jpg" alt="Bold Anime Reaction Thumbnail preview"></a>
<h3>Bold Anime Reaction Thumbnail</h3>
<p>Gaya thumbnail web anime berimpact tinggi dengan karakter reaksi besar, headline kuning-hitam raksasa, framing split-screen, reveal bercahaya cyan, dan ilustrasi cel-shaded yang bersih.</p>
<p><a href="styles/bold-anime-reaction-thumbnail-style/style.json"><strong>Buka style.json</strong></a> · <a href="docs/copy-prompts/bold-anime-reaction-thumbnail-style.md">Copy Prompt</a> · <a href="styles/bold-anime-reaction-thumbnail-style">Folder</a></p>
</td>
</tr>
</table>

## Struktur Paket

```text
styles/<style-slug>/
  style.json          # Template gaya prompt yang dapat dibaca mesin
  preview-16x9.jpg    # Preview landscape
  preview-9x16.jpg    # Preview portrait
```

## style.json v2.1

Setiap `style.json` bersifat mandiri: salin seluruh file ke LLM, lalu isi nilai untuk variabel yang dideklarasikan di `environment_variables` atau edit salah satu case di `examples[*].values`.

- `prompt_template` adalah prompt gaya reusable dengan placeholder `{VARIABLE}`.
- `environment_variables` mendeklarasikan semua placeholder yang dapat dipakai template.
- `examples` berisi kasus siap edit; setiap kasus hanya menyimpan `case_name` dan `values`.
- `style_fidelity_anchors` dan `source_content_to_avoid` menjelaskan apa yang harus dipertahankan dan apa yang tidak boleh disalin.
- `negative_prompt` membantu menghindari watermark, logo, rekreasi sumber langsung, dan output yang keluar dari gaya.

Prompt final seperti `prompt_9x16`, `prompt_16x9`, atau `full_prompt` sengaja tidak disimpan. Prompt itu dibuat saat generasi dari `prompt_template` dan nilai yang dipilih, sehingga JSON tetap ringkas dan tidak mudah basi.

Validasi pustaka dengan:

```bash
python3 scripts/validate-style-json.py .
```

## Indeks Gaya

| # | Gaya | Copy Prompt | File |
| --- | --- | --- | --- |
| 1 | [Mono Noir Type Portrait Poster Style](styles/mono-noir-type-portrait-poster-style) | [Copy Prompt](docs/copy-prompts/mono-noir-type-portrait-poster-style.md) | [style.json](styles/mono-noir-type-portrait-poster-style/style.json) |
| 2 | [Bold Block Mascot Poster Style](styles/bold-block-mascot-poster-style) | [Copy Prompt](docs/copy-prompts/bold-block-mascot-poster-style.md) | [style.json](styles/bold-block-mascot-poster-style/style.json) |
| 3 | [Blue HUD Macro Creator Tech Poster](styles/blue-hud-macro-product-poster) | [Copy Prompt](docs/copy-prompts/blue-hud-macro-product-poster.md) | [style.json](styles/blue-hud-macro-product-poster/style.json) |
| 4 | [Warm Fisheye Product Impact Ad](styles/warm-fisheye-product-impact-ad-style) | [Copy Prompt](docs/copy-prompts/warm-fisheye-product-impact-ad-style.md) | [style.json](styles/warm-fisheye-product-impact-ad-style/style.json) |
| 5 | [Olive Scribble Sports Poster](styles/olive-scribble-sports-poster-style) | [Copy Prompt](docs/copy-prompts/olive-scribble-sports-poster-style.md) | [style.json](styles/olive-scribble-sports-poster-style/style.json) |
| 6 | [Bold Anime Reaction Thumbnail](styles/bold-anime-reaction-thumbnail-style) | [Copy Prompt](docs/copy-prompts/bold-anime-reaction-thumbnail-style.md) | [style.json](styles/bold-anime-reaction-thumbnail-style/style.json) |
| 7 | [Turquoise Red Techno Manga Poster](styles/turquoise-red-techno-manga-poster-style) | [Copy Prompt](docs/copy-prompts/turquoise-red-techno-manga-poster-style.md) | [style.json](styles/turquoise-red-techno-manga-poster-style/style.json) |
| 8 | [Chromatic Fisheye Orbit Pop Poster](styles/chromatic-fisheye-orbit-pop-poster-style) | [Copy Prompt](docs/copy-prompts/chromatic-fisheye-orbit-pop-poster-style.md) | [style.json](styles/chromatic-fisheye-orbit-pop-poster-style/style.json) |
| 9 | [Naive Marker PSA Poster](styles/naive-marker-psa-poster-style) | [Copy Prompt](docs/copy-prompts/naive-marker-psa-poster-style.md) | [style.json](styles/naive-marker-psa-poster-style/style.json) |
| 10 | [Blue Bubble Fisheye Action Poster](styles/blue-bubble-fisheye-action-poster-style) | [Copy Prompt](docs/copy-prompts/blue-bubble-fisheye-action-poster-style.md) | [style.json](styles/blue-bubble-fisheye-action-poster-style/style.json) |
| 11 | [Cozy Bedroom Doodle Companion Snapshot](styles/cozy-bedroom-doodle-companion-snapshot-style) | [Copy Prompt](docs/copy-prompts/cozy-bedroom-doodle-companion-snapshot-style.md) | [style.json](styles/cozy-bedroom-doodle-companion-snapshot-style/style.json) |
| 12 | [Surreal Fish Doodle Landmark Photo Collage](styles/surreal-fish-doodle-landmark-photo-collage-style) | [Copy Prompt](docs/copy-prompts/surreal-fish-doodle-landmark-photo-collage-style.md) | [style.json](styles/surreal-fish-doodle-landmark-photo-collage-style/style.json) |
| 13 | [Plush Comic Toy Product Poster](styles/plush-comic-toy-product-poster-style) | [Copy Prompt](docs/copy-prompts/plush-comic-toy-product-poster-style.md) | [style.json](styles/plush-comic-toy-product-poster-style/style.json) |
| 14 | [Rough Animation Pet Sketch Storyboard](styles/rough-animation-pet-sketch-storyboard-style) | [Copy Prompt](docs/copy-prompts/rough-animation-pet-sketch-storyboard-style.md) | [style.json](styles/rough-animation-pet-sketch-storyboard-style/style.json) |
| 15 | [Tri Color Hardcut Portrait Poster](styles/tri-color-hardcut-portrait-poster-style) | [Copy Prompt](docs/copy-prompts/tri-color-hardcut-portrait-poster-style.md) | [style.json](styles/tri-color-hardcut-portrait-poster-style/style.json) |
| 16 | [Clean Triptych Travel Vlog Thumbnail](styles/clean-triptych-travel-vlog-thumbnail-style) | [Copy Prompt](docs/copy-prompts/clean-triptych-travel-vlog-thumbnail-style.md) | [style.json](styles/clean-triptych-travel-vlog-thumbnail-style/style.json) |
| 17 | [Playful Mascot Doodle Snapshot](styles/playful-mascot-doodle-snapshot-style) | [Copy Prompt](docs/copy-prompts/playful-mascot-doodle-snapshot-style.md) | [style.json](styles/playful-mascot-doodle-snapshot-style/style.json) |
| 18 | [Teenage Skate Scribble Screenprint Poster](styles/teenage-skate-scribble-screenprint-poster-style) | [Copy Prompt](docs/copy-prompts/teenage-skate-scribble-screenprint-poster-style.md) | [style.json](styles/teenage-skate-scribble-screenprint-poster-style/style.json) |
| 19 | [Impact Burst Halftone Comic Poster](styles/impact-burst-halftone-comic-poster-style) | [Copy Prompt](docs/copy-prompts/impact-burst-halftone-comic-poster-style.md) | [style.json](styles/impact-burst-halftone-comic-poster-style/style.json) |
| 20 | [Sunburst Fisheye Bubble Type Poster](styles/sunburst-fisheye-bubble-type-poster-style) | [Copy Prompt](docs/copy-prompts/sunburst-fisheye-bubble-type-poster-style.md) | [style.json](styles/sunburst-fisheye-bubble-type-poster-style/style.json) |
| 21 | [Backseat Transit Doodle Letter Poster](styles/backseat-transit-doodle-letter-poster-style) | [Copy Prompt](docs/copy-prompts/backseat-transit-doodle-letter-poster-style.md) | [style.json](styles/backseat-transit-doodle-letter-poster-style/style.json) |
| 22 | [Analog Sticker Diary Portrait Poster](styles/analog-sticker-diary-portrait-poster-style) | [Copy Prompt](docs/copy-prompts/analog-sticker-diary-portrait-poster-style.md) | [style.json](styles/analog-sticker-diary-portrait-poster-style/style.json) |
| 23 | [Folded Diamond Perspective Type Poster](styles/folded-diamond-perspective-type-poster-style) | [Copy Prompt](docs/copy-prompts/folded-diamond-perspective-type-poster-style.md) | [style.json](styles/folded-diamond-perspective-type-poster-style/style.json) |
| 24 | [Gothic Cat Doodle Photo Collage](styles/gothic-cat-doodle-photo-collage-style) | [Copy Prompt](docs/copy-prompts/gothic-cat-doodle-photo-collage-style.md) | [style.json](styles/gothic-cat-doodle-photo-collage-style/style.json) |
| 25 | [K-pop Apocalypse Ransom Zine](styles/k-pop-apocalypse-ransom-zine-style) | [Copy Prompt](docs/copy-prompts/k-pop-apocalypse-ransom-zine-style.md) | [style.json](styles/k-pop-apocalypse-ransom-zine-style/style.json) |
| 26 | [Metro Doodle Snapshot Diary](styles/metro-doodle-snapshot-diary-style) | [Copy Prompt](docs/copy-prompts/metro-doodle-snapshot-diary-style.md) | [style.json](styles/metro-doodle-snapshot-diary-style/style.json) |
| 27 | [Mountain Trail Monster Doodle Poster](styles/mountain-trail-monster-doodle-poster-style) | [Copy Prompt](docs/copy-prompts/mountain-trail-monster-doodle-poster-style.md) | [style.json](styles/mountain-trail-monster-doodle-poster-style/style.json) |
| 28 | [Neon Doodle Gallery Snapshot](styles/neon-doodle-gallery-snapshot-style) | [Copy Prompt](docs/copy-prompts/neon-doodle-gallery-snapshot-style.md) | [style.json](styles/neon-doodle-gallery-snapshot-style/style.json) |
| 29 | [Neon Kinetic Typographic Poster](styles/neon-kinetic-typographic-poster-style) | [Copy Prompt](docs/copy-prompts/neon-kinetic-typographic-poster-style.md) | [style.json](styles/neon-kinetic-typographic-poster-style/style.json) |
| 30 | [Orange Brush Mascot Action Poster](styles/orange-brush-mascot-action-poster-style) | [Copy Prompt](docs/copy-prompts/orange-brush-mascot-action-poster-style.md) | [style.json](styles/orange-brush-mascot-action-poster-style/style.json) |
| 31 | [Photo Illustration Overlay Poster](styles/photo-illustration-overlay-poster-style) | [Copy Prompt](docs/copy-prompts/photo-illustration-overlay-poster-style.md) | [style.json](styles/photo-illustration-overlay-poster-style/style.json) |
| 32 | [Plush City Festival Mobile Poster](styles/plush-city-festival-mobile-poster-style) | [Copy Prompt](docs/copy-prompts/plush-city-festival-mobile-poster-style.md) | [style.json](styles/plush-city-festival-mobile-poster-style/style.json) |
| 33 | [Pop Bubble Letter Photo Poster](styles/pop-bubble-letter-photo-poster-style) | [Copy Prompt](docs/copy-prompts/pop-bubble-letter-photo-poster-style.md) | [style.json](styles/pop-bubble-letter-photo-poster-style/style.json) |
| 34 | [Soft Analog Future Editorial Poster](styles/soft-analog-future-editorial-poster-style) | [Copy Prompt](docs/copy-prompts/soft-analog-future-editorial-poster-style.md) | [style.json](styles/soft-analog-future-editorial-poster-style/style.json) |
| 35 | [Subway Doodle Photo Hybrid](styles/subway-doodle-photo-hybrid-style) | [Copy Prompt](docs/copy-prompts/subway-doodle-photo-hybrid-style.md) | [style.json](styles/subway-doodle-photo-hybrid-style/style.json) |
| 36 | [Tokyo Kawaii Travel Collage Poster](styles/tokyo-kawaii-travel-collage-poster-style) | [Copy Prompt](docs/copy-prompts/tokyo-kawaii-travel-collage-poster-style.md) | [style.json](styles/tokyo-kawaii-travel-collage-poster-style/style.json) |
| 37 | [Urban Transit Doodle Diary](styles/urban-transit-doodle-diary-style) | [Copy Prompt](docs/copy-prompts/urban-transit-doodle-diary-style.md) | [style.json](styles/urban-transit-doodle-diary-style/style.json) |
| 38 | [Y2K Grunge Hip-hop Cutout Poster](styles/y2k-grunge-hiphop-cutout-poster-style) | [Copy Prompt](docs/copy-prompts/y2k-grunge-hiphop-cutout-poster-style.md) | [style.json](styles/y2k-grunge-hiphop-cutout-poster-style/style.json) |

## Model Publikasi

- Satu direktori = satu gaya
- Gaya baru muncul lebih dulu di Gaya Unggulan dan Indeks Gaya
- Branch main hanya berisi `style.json` dan dua preview JPG per gaya
- Galeri lengkap tidak disertakan di repo ini
- Jangan memublikasikan gambar referensi asli, watermark, identitas platform, QR code, handle akun, prompt privat, atau aset brand tanpa izin

## Lisensi

Struktur repo dan dokumentasi menggunakan lisensi MIT. Setiap file `style.json` menyatakan lisensinya sendiri. Gambar preview disertakan sebagai referensi visual.
