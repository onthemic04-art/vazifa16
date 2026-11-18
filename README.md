Loyiha maqsadi: Kompyuterdagi lokal kundalik repozitoriysini GitHub bulutli platformasiga joylashtirish, loyiha hujjati (README.md) yaratish hamda klonlash (clone) va yangilanishlarni olish (pull) amallarini bajarish.

1. Loyiha tuzilmasi va fayllar tarkibi
O‘tgan darsda yaratilgan mahalliy kundalik papkasida quyidagi asosiy fayllar jamlanadi:

Fayl nomi	Vazifasi va mazmuni	Holati (Public)
README.md	Loyihaning yuzi: loyiha nima haqida ekanligi, unda nimalar borligi va muallif haqida qisqa ma’lumot (shaxsiy ma’lumotlarsiz).	Push qilinadi
kundalik.md	O‘qilgan kitoblar va o‘quv mashg‘ulotlari haqidagi kundalik qaydnoma yozuvlari.	Push qilinadi
kitoblar.md	O‘qilgan va rejalashtirilgan kitoblar ro‘yxati.	Push qilinadi
orzular.md	Kelajakdagi maqsadlar va o‘quv rejalari yozilgan fayl.	Push qilinadi
2. README.md fayli namunasi
Loyihangiz papkasida README.md faylini yarating va ichiga quyidagi tuzilma asosida ma’lumot kiriting:

# Kundalik loyihasi

## Loyiha haqida
Ushbu repozitoriy 8-sinf informatika darsi doirasida Git va GitHub bilan ishlashni o‘rganish uchun yaratilgan o‘quv loyihasidir.

## Loyihada nimalar bor?
- `kundalik.md` — kunlik o‘quv qaydnomalari
- `kitoblar.md` — o‘qilgan kitoblar ro‘yxati
- `orzular.md` — o‘quv maqsadlari va rejalar

## Muallif
8-sinf o‘quvchisi (Git va GitHub asoslari kursi)
Xavfsizlik eslatmasi: Ochiq (Public) repozitoriyga parollar, telefon raqami, uy manzili, JSHSHIR, karta ma’lumotlari, .env fayllari hamda boshqalarning ruxsatsiz rasmlarini joylashtirish qat’iyan taqiqlanadi.
Kundalik loyihasi · Git va GitHub (16-dars)
Page 1 of 2
3. Git Bash orqali bajariladigan bosqichlar
1-bosqich: Lokal loyihani GitHub’ga chiqarish (1-topshiriq)
GitHub saytida kundalik nomli Public repozitoriy oching («Add a README file» katakchasini belgilamang), so‘ngra lokal kundalik papkasida quyidagi buyruqlarni bajaring:

git remote add origin https://github.com/[onthemic04-art]/kundalik.git
git remote -v
git push -u origin main
So‘ngra README.md faylini yaratib, uni saqlang va GitHub’ga yuboring:

git add README.md
git commit -m "README.md loyiha tavsifi qo'shildi"
git push
2-bosqich: «Ikkinchi kompyuter» sinovi (2-topshiriq)
Loyihani ish stolidagi alohida papkaga klonlang, GitHub saytida kundalik.md faylini tahrirlab commit qiling va yangilanishni tortib oling:

cd ~/Desktop
git clone https://github.com/[onthemic04-art]/kundalik.git kundalik-nusxa
cd kundalik-nusxa
git pull
