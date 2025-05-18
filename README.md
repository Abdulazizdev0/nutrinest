NutriNest – Bog‘cha Oshxonasi Boshqaruv Tizimi

NutriNest — bu bog‘chalardagi oshxona jarayonlarini soddalashtirish uchun ishlab chiqilgan zamonaviy raqamli boshqaruv tizimi. Tizim oshxona xodimlariga mahsulotlarni boshqarish, ovqatlarni nazorat qilish, avtomatik hisobotlar yaratish va ma’lumotlarni vizual ko‘rinishda tahlil qilish imkonini beradi.

Masshtablanadigan arxitektura va real vaqt rejimidagi funksiyalari bilan NutriNest oshxona boshqaruvini yanada shaffof, samarali va avtomatlashtirilgan qiladi.
📦 Funksiyalar

    Mahsulotlar boshqaruvi:

        Mahsulot nomi, miqdori (grammda), yetkazilgan sanasi

        Yangilash yoki o‘chirish

    Ovqatlar boshqaruvi:

        Ovqat nomi, ingredientlar, retseptlar

        Yangilash yoki o‘chirish

    Ovqat berish tizimi:

        Ovqat berilganda ingredientlar avtomatik kamayadi

        Yetarli bo‘lmasa xato xabari chiqadi

        Sana, vaqt va foydalanuvchi avtomatik qayd etiladi

    Porsiya hisoblash:

        Mavjud ingredientlar asosida avtomatik porsiya sonini hisoblaydi

    Hisobotlar va vizualizatsiya:

        Oylik hisobotlar (berilgan va mumkin bo‘lgan porsiyalar, farq foizi)

        Grafiklar: ingredient iste’moli, porsiya farqlari

    Foydalanuvchi rollari:

        Admin: to‘liq boshqaruv (foydalanuvchilar, mahsulotlar, ovqatlar, hisobotlar)

        Oshpaz: faqat ovqat berish funksiyasi

        Menejer: omborni yangilash, tahlillarni ko‘rish

    Ogohlantirishlar:

        Ingredientlar miqdori minimumdan kamaysa

        Oylik porsiya farqi 15% dan oshsa

    Fon vazifalari (Celery yordamida):

        Oylik hisobotlarni avtomatik yaratish

        Porsiyalarni qayta hisoblash

    Real vaqt yangilanishlari:

        Ombordagi holat va kamaygan ingredientlar haqida WebSocket orqali ogohlantirishlar

🛠 Texnologiyalar

    Backend: Django, Django REST Framework, Django Channels (WebSocket)

    Frontend: React (API orqali integratsiya)

    Ma’lumotlar bazasi: PostgreSQL

    Fon vazifalari: Celery + Redis

    Vizualizatsiya: Chart.js

    Versiya boshqaruvi: Git

👤 Foydalanish

    Admin: Mahsulotlar, ovqatlar, foydalanuvchilar va hisobotlarni boshqaradi.

    Oshpaz: Ovqat berish funksiyasidan foydalanib, ovqatlarni qayd etadi.

    Menejer: Ombor ma’lumotlarini yangilaydi va vizual tahlillarni ko‘radi.

    Frontend ogohlantirishlari: Kam mahsulot yoki katta farqlar haqida real vaqt bildirishnomalari.