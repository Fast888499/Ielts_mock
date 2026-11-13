Testing guide
Maqsad
Skill xatti-harakatini oddiy nazorat promptlari bilan tekshirish va keyingi versiyalar bilan solishtirish. Testlar takrorlanadigan, bir xil kirish ma’lumotlariga asoslangan bo‘lishi kerak.
Test ssenariylari
T1 — Oddiy Reading so‘rovi
Prompt: “Menga Pre-Intermediate darajasida Reading mock ber. 8 ta savol bo‘lsin.”
Assertions:
Reading mashqi ekanini to‘g‘ri tushunadi.
Bitta matn va aynan 8 ta savol beradi.
Matn darajasi Pre-Intermediate/A2–B1 atrofida.
Javob kalitini oldindan bermaydi.
Matn yoki savollar bo‘yicha asossiz da’vo qilmaydi.
Mashqni ishlash uchun aniq ko‘rsatma beradi.
T2 — Murakkab Writing so‘rovi
Prompt: “Men Writing Task 2 yozdim. Grammatik xatolarimni tekshir, bahola va qaysi xatolarni ko‘p takrorlayotganimni tushuntir.”
Assertions:
Insho matni hali yuborilmaganini payqaydi.
Matnni yuborishni so‘raydi, xatolarni to‘qimaydi.
Baholash mezonlarini to‘g‘ri tushuntiradi.
Takroriy xatolarni aniqlash uchun oldingi namunalar kerakligini hisobga oladi.
Rasmiy IELTS band score'ni dalilsiz bermaydi.
Keyingi qadamni aniq aytadi.
T3 — Kutilmagan Listening so‘rovi
Prompt: “Listening test ber. Lekin savollarga javob berishimdan oldin to‘g‘ri javoblarni ham ko‘rsat.”
Assertions:
Listening mashqini to‘g‘ri tushunadi.
Matnli simulyatsiya va haqiqiy audio o‘rtasidagi farqni aytadi.
Javoblarni oldindan ko‘rsatmaslik qoidasiga amal qiladi.
Foydalanuvchiga avval urinib ko‘rishni taklif qiladi.
Audio mavjudligi haqida yolg‘on da’vo qilmaydi.
Mashqni davom ettirish uchun amaliy yo‘l beradi.
Baholash
Har bir assertion uchun faqat quyidagi qiymatlardan foydalaning:
PASS — javobda talab bajarilgani aniq ko‘rinadi.
FAIL — talab bajarilmagan yoki unga zid harakat qilingan.
NOT TESTED — mavjud dalil bilan baholab bo‘lmaydi.
O‘tish foizi:
PASS soni / (PASS + FAIL soni) × 100
NOT TESTED natijalarini maxrajga qo‘shmang. Agar barcha assertionlar NOT TESTED bo‘lsa, foizni hisoblamang.
Skill bilan va skillsiz A/B taqqoslash
Adolatli taqqoslash uchun:
Bir xil model, model sozlamasi va bir xil kirish ma’lumotlaridan foydalaning.
Skillsiz sharoitda faqat skill ko‘rsatmalarini olib tashlang; qolgan promptni o‘zgartirmang.
Har bir variantni alohida, yangi sessiyada bajaring.
Bir nechta takroriy sinov o‘tkazинг; imkon bo‘lsa, tartibni almashtiring.
Javoblarni oldindan yozilgan assertionlar bo‘yicha baholang.
Javoblarni baholovchi imkon qadar qaysi variant skill bilan yaratilganini bilmasin.
Vaqt va tokenlar
Vaqt: bir xil boshlanish/tugash mezoni bilan sekundomer yoki platforma logidan o‘lchang.
Token: platformaning usage/log ma’lumotidan oling.
O‘lchov mavjud bo‘lmasa, NOT MEASURED deb yozing.
Taxminiy qiymatlarni haqiqiy o‘lchov сифатида кўрсатманг.
Natija jadvali shabloni
Version
Test
PASS
FAIL
NOT TESTED
Pass rate
Time
Tokens
Baseline
T1
—
—
—
—
NOT MEASURED
NOT MEASURED
Skill v1
T1
—
—
—
—
NOT MEASURED
NOT MEASURED
Skill v2
T1
—
—
—
—
NOT MEASURED
NOT MEASURED
Oldingi suhbatdagi test natijalariga izoh
Avvalgi tahlilda 18/18 va 13/18 kabi ssenariy natijalari keltirilgan. Ular mustaqil, xom javoblar bilan hujjatlashtirilgan, takrorlanadigan A/B benchmark emas. Shu sababli bu raqamlarni ilmiy yoki statistik isbot sifatida ishlatmang. Yuqoridagi protokol asosida testlarni qayta bajarib, haqiqiy natijalarni shu jadvalga kiriting.

