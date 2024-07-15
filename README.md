![Logo](https://candokendo.wordpress.com/wp-content/uploads/2020/08/sass.jpeg?w=792)



<div align="center">

## SCSS-MODULES
## SCSS-STARTER
</div>

## Muallif: Jasur Haydarov ([jasurhaydarovcode](https://github.com/jasurhaydarovcode))

---

### NPM Yordamida Structurani O'rnatish
```bash
npm i scss-mods
```

## Loyihaning fayl structurasi
```paintext
project-folder/
│
├── index.html
├── scss/
│   ├── main.scss
│   ├── _variables.scss
│   ├── _mixins.scss
│   ├── _base.scss
│   ├── components/
│   │   ├── _header.scss
│   │   ├── _footer.scss
│   │   ├── _navbar.scss
│   │   ├── _button.scss
│   │   └── _card.scss
│   ├── layout/
│   │   ├── _grid.scss
│   │   ├── _header.scss
│   │   ├── _footer.scss
│   │   ├── _sidebar.scss
│   │   └── _main.scss
│   ├── pages/
│   │   ├── _home.scss
│   │   ├── _about.scss
│   │   ├── _contact.scss
│   │   └── _product.scss
│   └── utils/
│       ├── _functions.scss
│       ├── _mixins.scss
│       └── _variables.scss
└── css/
    └── main.css
```

---

# NPM Yordamida `SASS`ni O'rnatish
## 1. NPM Initialize qilib oling
```bash
npm init -y
```
## 2. Terminal yordamida default fayllarni yaratib olamiz
```bash
mkdir scss
mkdir css
```

## 3. SCSS (Sass) paketini o'rnatish
#### SCSS kompilyatorini sass o'rnatish
```bash
npm install sass
```

agarda `dev dependeses` ga o'rnatmoqchi bo'lsangiz

```bash
npm install sass --save-dev
```


## 4. SCSS fayllarini kompilyatsiya qilish uchun skript qo'shish
`package.json` faylingizda `scripts` bo'limiga quyidagi skriptni qo'shing:

```json
"scripts": {
  "sass": "sass --watch scss:css"
}
```
Bu skript `.scss` faylini `.css` fayliga avtomatik kompilyatsiya qilish uchun ishlatiladi.

## 5. SCSS fayllarini kompilyatsiya qilish
```bash
npm run sass
```

Bu buyruq `scss` faylini kuzatadi va har bir o'zgarishdan so'ng `css`.css faylini yangilaydi.

## 6. HTML faylda CSS faylini ulash
index.html faylingizda kompilyatsiya qilingan CSS faylini ulash uchun quyidagi qatorni `<head>` tegiga qo'shing:
```html
<link rel="stylesheet" href="css/main.css">
```
---

# EXAMPLE 

## Tugallangan `package.json` fayli misoli

```json
{
  "name": "project-folder",
  "version": "1.0.0",
  "description": "",
  "main": "index.js",
  "scripts": {
    "sass": "sass --watch scss:css"
  },
  "author": "",
  "license": "ISC",
  "devDependencies": {
    "sass": "^1.32.8"
  }
}
```

Mana shu qo'llanma yordamida loyihangizda SCSS dan foydalanishni boshlashingiz mumkin. Agar qo'shimcha yordam kerak bo'lsa, `issue`dan bemalol so'rang!

---

## Hissangiz
### Agar siz ushbu repoga hissa qo'shmoqchi bo'lsangiz, iltimos `fork` dan foydalaning.

---

# ALOQA
#### Agar sizda savollar yoki takliflar bo'lsa, iltimos, [email manzilingiz yoki aloqa usulingizni] orqali bog'laning.