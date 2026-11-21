Mantiqiy topshiriqlar javoblari


3-topshiriq (Ali va Malika):
- 10:00 da Ali muvaffaqiyatli push qildi.
- 10:20 da Malika commit qildi (muvaffaqiyatli).
- 10:25 da Malika push qila olmaydi (rad etildi), chunki Ali undan oldin o'zgarish kiritgan. Malika avval "git pull" qilib, so'ng "git push" qilishi kerak.
- Qoida: Har doim ishni boshlashdan oldin "git pull" qilish kerak.

4-topshiriq (Xavfsizlik):
- README.md — Ha (loyiha tavsifi, xavfsiz).
- parollar.txt — Yo'q (maxfiy ma'lumot, parol oshkor bo'lib qoladi).
- O'zim chizgan robot rasmi — Ha (shaxsiy ijod).
- Sinfdoshimning surati (ruxsatsiz) — Yo'q (shaxsiy maxfiylik va huquq buziladi).
- manzil.md — Yo'q (shaxsiy manzil va telefon raqami xavfsiz emas).
- kundalik.md — Ha (o'qilgan kitoblar).
- .env — Yo'q (maxfiy kalitlar va parollar saqlanadi).
- Maktab loyihamning kodi — Ha (o'quv loyihasi).
- Agar parollar.txt push qilingan bo'lsa: Faylni o'chirish yetarli emas, chunki eski commit'larda qolib ketadi. Parollarni zudlik bilan o'zgartirish kerak.

5-topshiriq (Qaysi buyruq?):
- Yangi noutbukda olish: git clone <URL>
- GitHub manziliga ulash: git remote add origin <URL>
- Manzilni tekshirish: git remote -v
- Birinchi marta yuborish: git push -u origin main
- Ertalab ishni boshlashdan oldin: git pull
- Kechqurun ish tugagach: git push

6-topshiriq (Detektiv - Ali):
a) Dushanba (C1) va seshanba (C2, C3) commit'larini qaytara oladi, chunki ularni oxirgi marta push qilgan. Chorshanba va payshanba kungi commit'lar yo'qoladi.
b) .git papkasi buzilgan kompyuterda qolgani uchun tarix ham birga yo'qoladi.
c) Har kuni kechqurun ish tugagach "git push" qilish odatini chiqarish kerak edi.