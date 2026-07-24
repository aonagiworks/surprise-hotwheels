# Surprise Website 🏎️ Hot Wheels Edition

Web surprise personal: **PIN gate** + **tema racing / Hot Wheels**.

## Flow
1. Layar PIN (6 digit) — “Start Your Engine”
2. Hero birthday + mobil floating + confetti
3. Tombol **GAS POL!** → pit stop memories

## Customize (`index.html` — script bawah)

```js
const PW = "130605";        // PIN
const RECIPIENT = "SAYANG"; // nama di hero
```

| Data | Lokasi |
|------|--------|
| PIN + petunjuk | `PW` + teks `.hint` |
| Nama | `RECIPIENT` |
| Ucapan | `#mainMessage` |
| Foto | `.pic` di gallery → ganti jadi `<img>` |
| Lagu | hubungkan di `#musicBtn` |

## Preview
```bash
cd ~/surprise-website
python3 -m http.server 8080
# http://localhost:8080 — PIN: 130605
```

## Tema
Merah / oranye / kuning, checkerboard, flag finish, racing cars.

© 2026 Aonagi Works
