# BLOG APPLICATION

## Kirish
> Bu Django-ga asoslangan blog ilovasi bo'lib, foydalanuvchilarga blog postlarini yaratish, o'qish, yangilash va o'chirish imkonini beradi. U blog mazmunini boshqarish uchun qulay interfeysni taqdim etadi va foydalanuvchi autentifikatsiyasi, sharhlar tizimi va qidiruv funksiyalari kabi muhim xususiyatlarni qo‘llab-quvvatlaydi. Ushbu readme fayli sizga ilovani sozlash va undan foydalanish bo'yicha yo'l-yo'riq ko'rsatadi.
![todo App](https://github.com/abubakirovxolmirza/b/blob/main/staticfiles/todoApp.png)

## Talablar
> Ushbu Django blog ilovasini ishga tushirish uchun kompyuteringizda quyidagi dastur oʻrnatilgan boʻlishi kerak:

 Python (version 3.6 or higher)

Django (version 3.0 or higher)

### O'rnatish
```bash
$ git clone https://github.com/abubakirovxolmirza/blog-application
```
 Ushbu ilovani ishga tushirish uchun administrator foydalanuvchi yaratishimiz kerak. Terminalda quyidagi buyruqni kiriting va administrator foydalanuvchi uchun foydalanuvchi nomi, parol va elektron pochta manzilini kiriting
```bash
$ python manage.py createsuperuser
```
Biz serverni hozir ishga tushirishimiz kerak, shundan so'ng biz todoapp ilovasidan foydalanishni boshlashimiz mumkin. Quyidagi buyruq bilan serverni ishga tushiring
```bash 
$ python manage.py runserver
```

Server joylashtirilgandan so'ng, ilova uchun http://127.0.0.1:8000/todos manziliga o'ting.

