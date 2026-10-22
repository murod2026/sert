# Uyg'un ta'lim — sertifikat tekshiruvi

«UYG'UN TA'LIM» MChJ bergan sertifikatlarni tekshirish sahifasi.

- `index.html` — QR kod yoki qo'lda kiritilgan raqam + kod bo'yicha tekshirish
- `bitiruvchilar.html` — e'lon qilinishiga rozilik bergan bitiruvchilar ro'yxati
- `logo.svg` — brendbukdagi logotip (vektor)

Sahifalar statik: ma'lumot Supabase RPC orqali to'g'ridan-to'g'ri brauzerdan olinadi.
Serverda hech qanday shaxsiy ma'lumot saqlanmaydi.

Ishlatiladigan funksiyalar: `sertifikat_tekshirish`, `bitiruvchilar_soni` va `bitiruvchilar` ko'rinishi.
