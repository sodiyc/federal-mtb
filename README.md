# 🚲 Federal MTB — Arsip Sepeda Nasional

> Basis data komunitas terlengkap untuk sepeda **Federal MTB** buatan Indonesia.  
> Dibangun oleh penggemar, untuk penggemar — _Federal Riders Indonesia_.

---

## 🌐 Buka Aplikasi

👉 **[MTB Federal Cycle](https://sodiyc.github.io/federal-mtb/index.html)**

---

## ✨ Fitur Utama

| Fitur | Keterangan |
|---|---|
| 📖 **Katalog Model** | 50+ model Federal MTB dari semua seri — Seri Kucing, Macan, Gunung, Road, Terrain |
| 🔍 **Decoder Nomor Seri** | Baca pabrik, tahun, bulan, dan nomor urut dari kode rangka |
| 🗄️ **Database SN Komunitas** | Arsip nomor seri terverifikasi dari seluruh Indonesia |
| 🤝 **Kontribusi Online** | Tambah nomor seri langsung ke database komunitas (tersimpan online) |
| 📤 **Export JSON** | Download seluruh data komunitas untuk backup |

---

## 🏷️ Seri Sepeda yang Tercakup

- **Seri Kucing** — AlleyCat, BigCat, BobCat, CityCat, MuddyCat, StreetCat, TomCat, WildCat, dll.
- **Seri Macan** — Cheetah, Jaguar, Kougar, Panther Competition, dll.
- **Seri Gunung** — Alpenz Peak, Cartenz Peak, Mt Everest, Rock Blazer, dll.
- **Seri Road** — Alpha, Beta, Bolero Aeroglide, Rainbow, Suprimo Aeroglide, dll.
- **Seri Terrain** — Monaco, Rivera, Torino, Valencia Terrain, dll.
- **Seri X-Cross & Metal Craft**

---

## 🔢 Format Nomor Seri Federal

```
FC  33  Y  00582
│   │   │  └── Nomor urut produksi
│   │   └───── Bulan (X=Okt, Y=Nov, Z=Des, 1-9=Jan-Sep)
│   └───────── Tahun produksi (33 = 1993)
└───────────── Kode pabrik (FC = Federal Cycle)
```

**Kode Bulan:**
`1`=Jan · `2`=Feb · `3`=Mar · `4`=Apr · `5`=Mei · `6`=Jun  
`7`=Jul · `8`=Agu · `9`=Sep · `X`=Okt · `Y`=Nov · `Z`=Des

---

## 🤝 Cara Berkontribusi

Punya sepeda Federal? Bantu perluas arsip komunitas!

1. Buka aplikasi di link di atas
2. Klik tab **"Kontribusi"**
3. Isi nomor seri, nama model, dan keterangan
4. Klik **"Simpan ke Arsip Komunitas"**

Data Anda langsung tersimpan online dan bisa dilihat seluruh komunitas. 🙌

---

## 🛠️ Teknologi

- **Frontend:** HTML5 + CSS3 + Vanilla JavaScript (single file, no framework)
- **Database:** [Supabase](https://supabase.com) (PostgreSQL, realtime)
- **Hosting:** GitHub Pages
- **Font:** Playfair Display, Libre Baskerville, Special Elite (Google Fonts)

---

## 📁 Struktur Repository

```
federal-mtb/
├── index.html        ← Aplikasi utama (semua dalam satu file)
└── README.md         ← Halaman ini
```

---

## 📜 Tentang Proyek Ini

Proyek ini lahir dari kecintaan komunitas terhadap sepeda Federal MTB — sepeda legendaris Indonesia yang berjaya di era 1990-an. Tujuannya adalah melestarikan sejarah dan membantu sesama kolektor mengidentifikasi sepeda mereka.

**Federal Cycle Manufacturing** adalah produsen sepeda Indonesia yang dikenal lewat seri-seri ikonik seperti StreetCat, MuddyCat, dan Alpenz Peak yang banyak diburu kolektor hingga hari ini.

---

## 📣 Komunitas

- 🔵 **Facebook:** Federal Bike Indonesia
- 📸 **Instagram:** #federalmtb #federalbike #sepedafederal

---

## ⚖️ Lisensi

Data komunitas bersifat terbuka — bebas digunakan untuk keperluan non-komersial dengan menyebut sumbernya.

---

<div align="center">
  <sub>Dibuat dengan ❤️ oleh komunitas Federal Riders Indonesia</sub>
</div>
