# Arab tili → o‘zbek tili tarjima loyihasi

Bu repository Codex yordamida arabcha matnlarni yuqori sifatli o‘zbek tiliga tarjima qilish uchun mo‘ljallangan.

## Asosiy qoida

Arabcha matnni darhol tarjima qilma. Avval ma'nosini filologik jihatdan aniqlab ol, keyin tarjima qil va oxirida original bilan tekshir.

## Skilllardan foydalanish

Loyiha ichidagi `.agents/skills/` skilllaridan tegishli vazifaga qarab foydalan:

- `arabic-text-analysis` — barcha jiddiy tarjimalardan OLDIN. Nahv, sarf, i‘rob, lug‘at, balog‘at, kontekst va register tahlili.
- `scientific-arabic-translation` — ilmiy, akademik, tarixiy, pedagogik, lingvistik va texnik matnlar.
- `literary-arabic-translation` — badiiy, hikoya, roman, maqola va obrazli nasr.
- `islamic-classical-translation` — Qur’on, hadis, tafsir, aqida, fiqh, usul, tarjimai hol va klassik ilmiy arabcha.
- `arabic-uzbek-terminology` — takrorlanuvchi ilmiy va diniy terminlarni izchil saqlash; uzun asarlar uchun terminology map tuzish.
- `translation-review` — muhim tarjimalardan KEYIN original va tarjimani qat’iy solishtirish.

Agar janr noaniq bo‘lsa, avval `arabic-text-analysis` bilan register va janrni aniqlang.

## Standart ish jarayoni

### 1. Source preservation
- Arabcha originalni o‘zgartirma.
- Harakatlar, imlo, iqtiboslar, raqamlar, ism va kitob nomlarini asossiz tuzatma.
- Tushunarsiz joyni taxmin bilan to‘ldirma.

### 2. Analysis
`arabic-text-analysis` orqali:
- nahv va zarur i‘rob;
- sarf va so‘z yasalishi;
- kontekstual lug‘aviy ma’no;
- idiomalar;
- balog‘at va badiiy vositalar;
- texnik terminlar;
- zamirlarning qaytishi;
- muallifning aniqlik darajasi va modal ma’nolarini aniqlang.

### 3. Translation
- So‘zma-so‘z tarjimani maqsad emas, vosita deb bil.
- Birlamchi mezon: MA’NO ANIQLIGI.
- Keyingi mezon: tabiiy va savodli o‘zbek tili.
- Ilmiy matnda terminologik aniqlik va mantiqiy bog‘lanishlarni saqla.
- Badiiy matnda obraz, ohang, ritm, kinoya, tashbeh va muallif ovozini saqla.
- Diniy/klassik matnda established terminlarni afzal ko‘r va muallif aytmagan sharhni tarjimaga qo‘shma.

### 4. Terminology
- Bir asar ichida bir xil arabcha terminni imkon qadar bir xil o‘zbekcha ekvivalent bilan ber.
- Texnik ma’no bilan lug‘aviy ma’noni aralashtirma.
- Ishonchli o‘zbekcha ekvivalent bo‘lmasa, arabcha terminni transliteratsiya yoki qavs ichidagi asl shakl bilan saqlash mumkin.
- Terminlarni o‘zingcha uydirma.

### 5. Review
Muhim yoki uzun tarjimada `translation-review`ni ishlat.
Tekshir:
- tushib qolgan gap/ibora;
- qo‘shib yuborilgan ma’no;
- inkor va tasdiq;
- ega-kesim va zamirlar;
- sabab/oqibat, shart, istisno va qarama-qarshilik;
- son, sana va ism;
- terminlar izchilligi;
- uslub va o‘zbekcha tabiiylik.

## Tarjima uslubi

Default o‘zbek tili:
- adabiy;
- tabiiy;
- grammatik jihatdan to‘g‘ri;
- ilmiy matnda akademik;
- badiiy matnda badiiy;
- diniy matnda ilmiy va ehtiyotkor.

O‘zbekcha gapni arabcha sintaksisga majburan taqlid qildirma. Lekin ravonlik uchun original ma’nosini o‘zgartirma.

## Qat’iy taqiqlar

- Manbada yo‘q ma’lumotni qo‘shma.
- Manbadagi ma’noni tushirib qoldirma.
- Muallifning fikrini kuchaytirma yoki zaiflashtirma.
- "Ehtimol", "ko‘rinadi", "aytilishicha" kabi noaniqliklarni asossiz ravishda qat’iy faktga aylantirma.
- Hadis, oyat, iqtibos, kitob yoki shaxsga asossiz manba va nisbat kiritma.
- Bilmagan narsangni to‘qima.

## Javob formati

Agar foydalanuvchi faqat "tarjima qil" desa, default ravishda yakuniy, silliqlangan o‘zbekcha tarjimani ber.

Agar matn murakkab bo‘lsa, tarjimadan OLDIN qisqa "Tahlil" bo‘limi berish mumkin, ammo foydalanuvchi faqat tarjimani so‘ragan bo‘lsa, keraksiz tahlil bilan javobni cho‘zma.

Agar jiddiy noaniqlik bo‘lsa, uni tarjimaga yashirmasdan alohida "Tarjimon izohi" sifatida ko‘rsat.

## Muhim

Uzun kitob yoki bob tarjima qilinayotgan bo‘lsa, avval terminology map tuz va keyingi bo‘limlarda undan foydalan. Har bir yangi bo‘limni oldingi terminologiya va uslub bilan muvofiqlashtir.
