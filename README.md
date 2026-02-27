# 📝 Dars - 2 (27.02.2026)

## 1. Matnni formatlash (Formatting)
HTML’da matn ko‘rinishini o‘zgartirish uchun quyidagi teglardan foydalaniladi:

* `<b></b>` — Qalin matn (**Bold**)
* `<i></i>` — Kursiv matn (*Italic*)
* `<strong></strong>` — Muhim matn (Vizual qalin)
* `<em></em>` — Urg'u berilgan matn (Vizual kursiv)
* `<mark></mark>` — Belgilangan matn (Sariq fon)
* `<sub></sub>` — Pastki indeks (Masalan: H₂O)
* `<sup></sup>` — Yuqori indeks (Masalan: m²)

---

## 2. Sharhlar (Comments)
Kodni tushuntirish yoki vaqtincha yashirib turish uchun ishlatiladi. Brauzerda ko‘rinmaydi.

**Sintaksis:**
`<!-- -->`

**Vazifasi:**
* Dasturchilar o'rtasidagi tushunmovchiliklarning oldini oladi.
* HTML fayldagi ishlatilmaydigan kodlarni o'chirib tashlamasdan yashirib qo'yish imkonini beradi.

---

# 3 - 4 - 5. CSS-ni ulash usullari

CSS (Cascading Style Sheets) kodlarini HTML-ga 3 xil usulda ulash mumkin:

### 1) Inline Styles (Qator ichidagi uslublar)
Bevosita elementning ichida `style` atributi orqali yoziladi.
```html
<h1 style="color: red; font-weight: bold; text-decoration: underline;">Hello</h1>
```

### 2)Internal Styles (Ichki uslublar)
   HTML hujjatining `<head>` qismida `<style>` tegi ichida yoziladi.

```html
<style>
    h1 {
        color: red;
        font-weight: bold;
        text-decoration: underline;
    }
</style>
```

### 3) External Styles (Tashqi uslublar)
   Alohida `.css` fayli yaratiladi va HTML-ga `<link>` tegi orqali ulanadi. Bu eng ko'p qo'llaniladigan usul.
   
```html
<link rel="stylesheet" href="./style.css">
```

# Tugadi bugungi mavzu