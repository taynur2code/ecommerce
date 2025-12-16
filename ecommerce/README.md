# 🛒 MegaMart E-Commerce Platform

Modern və responsive e-commerce landing page layihəsi. Vue.js 3 və Vite ilə hazırlanmış, pixel-perfect dizayn və komponent əsaslı arxitektura.

![Vue.js](https://img.shields.io/badge/Vue.js-3.5.22-4FC08D?style=for-the-badge&logo=vue.js&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-7.1.11-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Vue Router](https://img.shields.io/badge/Vue_Router-4.6.3-4FC08D?style=for-the-badge&logo=vue.js&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

## 📋 Məzmun

- [Haqqında](#-haqqında)
- [Xüsusiyyətlər](#-xüsusiyyətlər)
- [Texnologiyalar](#-texnologiyalar)
- [Quraşdırma](#-quraşdırma)
- [İstifadə](#-istifadə)
- [Layihə Strukturu](#-layihə-strukturu)
- [Komponentlər](#-komponentlər)
- [Lisenziya](#-lisenziya)
- [Əlaqə](#-əlaqə)

## 🎯 Haqqında

MegaMart müasir e-commerce platformasının landing page-idir. Layihə Vue.js 3 Composition API istifadə edərək hazırlanıb və tamamilə komponent əsaslı arxitekturaya malikdir. Pixel-perfect dizayn, responsive layout və istifadəçi təcrübəsinə fokuslanıb.

### ✨ Demo

🔗 [Canlı Demo](https://github.com/taynur2code/ecommerce)

## 🚀 Xüsusiyyətlər

- ⚡ **Sürətli Performans** - Vite build tool ilə dəstək
- 🎨 **Pixel-Perfect Dizayn** - Dəqiq koordinat sistemi ilə yerləşdirmə
- 🧩 **Komponent Əsaslı** - Təkrar istifadə edilə bilən Vue komponentləri
- 📱 **Responsive** - Bütün ekran ölçüləri üçün uyğunlaşdırıla bilir
- 🎭 **Dinamik Məzmun** - Props vasitəsilə idarə olunan komponentlər
- 🛣️ **Vue Router** - SPA naviqasiya sistemi
- 🎯 **Modern UI/UX** - İstifadəçi dostu interfeys
- 🌈 **Hover Effektləri** - İnteraktiv vizual elementlər

## 🛠️ Texnologiyalar

### Frontend Framework
- **Vue.js 3.5.22** - Progressive JavaScript Framework
- **Composition API** - Modern Vue sintaksisi

### Build Tool & Development
- **Vite 7.1.11** - Yeni nəsil frontend build tool
- **@vitejs/plugin-vue 6.0.1** - Vue 3 SFC dəstəyi
- **Vue DevTools 8.0.3** - Development zamanı debugging

### Routing
- **Vue Router 4.6.3** - Rəsmi Vue.js router

### Dizayn Sistemi
- **Custom CSS** - Scoped styling
- **Mütləq Pozisiyalaşdırma** - Pixel-perfect layout
- **Fixed Positioning** - Vertikal səhifə strukturu

### Asset Management
- **SVG Icons** - Vektor qrafika
- **Optimizasiya edilmiş şəkillər** - Public folder strukturu

## 📦 Quraşdırma

### Tələblər

- Node.js (v20.19.0 və ya v22.12.0+)
- npm və ya yarn

### Addımlar

1. **Repository-ni klonlayın**
```bash
git clone https://github.com/taynur2code/ecommerce.git
cd ecommerce
```

2. **Asılılıqları quraşdırın**
```bash
npm install
# və ya
yarn install
```

3. **Development serveri işə salın**
```bash
npm run dev
# və ya
yarn dev
```

4. **Brauzerə keçin**
```
http://localhost:5173
```

## 💻 İstifadə

### Development

Development rejimində hot-reload ilə işləmək:

```bash
npm run dev
```

### Production Build

Production üçün optimize build:

```bash
npm run build
```

### Preview

Build nəticəsini yerli olaraq preview etmək:

```bash
npm run preview
```

## 📁 Layihə Strukturu

```
ecommerce/
├── public/                    # Statik assetlər
│   ├── aynur/                # Kateqoriya və brend şəkilləri
│   │   ├── dairy.svg
│   │   ├── return.svg
│   │   └── mask.svg
│   ├── brands/               # Elektronika brendləri
│   │   ├── Group 50.svg
│   │   ├── Group 51.svg
│   │   └── Group 52.svg
│   ├── contact/              # Əlaqə ikonları
│   │   ├── 60.svg
│   │   ├── 61.svg
│   │   └── 200.svg
│   ├── productdeal/          # Məhsul şəkilləri
│   ├── productshoping/       # Kateqoriya şəkilləri
│   └── productdaily/         # Gündəlik məhsullar
├── src/
│   ├── assets/               # Stillar
│   │   ├── base.css
│   │   └── main.css
│   ├── components/           # Vue komponentləri
│   │   ├── Navbar.vue        # Üst naviqasiya bar
│   │   ├── Navbar2.vue       # Əsas naviqasiya
│   │   ├── Category.vue      # Kateqoriya naviqasiyası
│   │   ├── Carousel.vue      # Promo carousel
│   │   ├── Deal.vue          # Smartphone təkliflər
│   │   ├── ProductCard.vue   # Təkrar istifadə edilən kart
│   │   ├── TopCategories.vue # Üst kateqoriyalar
│   │   ├── CategoryCard.vue  # Dairəvi kateqoriya kartı
│   │   ├── ElectronicsBrands.vue # Brend showcase
│   │   ├── DailyEssentials.vue   # Gündəlik məhsullar
│   │   ├── EssentialsCard.vue    # Məhsul kartı
│   │   └── Footer.vue        # Footer komponenti
│   ├── App.vue               # Root komponent
│   └── main.js               # Entry point
├── index.html                # HTML template
├── vite.config.js            # Vite konfiqurasiyası
├── jsconfig.json             # JavaScript konfiqurasiyası
├── package.json              # Asılılıqlar və scriptlər
└── README.md                 # Layihə dokumentasiyası
```

## 🧩 Komponentlər

### Naviqasiya Komponentləri
- **Navbar** - Promo mesaj və utility linkləri
- **Navbar2** - Brend loqo, axtarış və istifadəçi naviqasiyası
- **Category** - Horizontal kateqoriya filterləri

### Məzmun Komponentləri
- **Carousel** - Promo banner dekorativ elementlərlə
- **Deal** - Smartphone təkliflər bölməsi
- **ProductCard** - Endirim badge, qiymət və yadda saxlama məlumatları
- **TopCategories** - Dairəvi kateqoriya iconları
- **ElectronicsBrands** - Brend loqo showcase
- **DailyEssentials** - Meyvə və ərzaq məhsulları

### Footer
- **3 bölmə strukturu** - Contact, Categories, Services
- **Hover effektləri** - İnteraktiv elementlər
- **Dekorativ grafikalar** - Mask SVG dizaynı

### Props Sistemi
Komponentlər dinamik məzmun üçün props qəbul edir:

```vue
<ProductCard 
  product-image="/productdeal/phone.jpg"
  product-name="Galaxy S22 Ultra"
  current-price="₹32999"
  original-price="₹74999"
  save-amount="₹32999"
/>
```

## 🎨 Dizayn Sistemi

### Rəng Paleti
- **Primary Blue**: `#008ECC`
- **Text Gray**: `#666666`
- **Light Background**: `#F5F5F5`, `#F3F3F3`
- **Dividers**: `#D9D9D9`
- **Success Green**: `#249B3E`
- **Dark Text**: `#222222`
- **White**: `#FFFFFF`
- **Accent Blue**: `#05ABF3`

### Border Radius
- **Standard Cards**: `8px`
- **Special Elements**: `16px`
- **Circular**: `50%`

### Pozisiyalaşdırma
- Fixed positioning əsas səhifə bölmələri üçün
- Absolute positioning uşaq elementlər üçün
- Pixel-perfect koordinat sistemi

## 📄 Lisenziya

Bu layihə MIT Lisenziyası altında lisenziyalaşdırılıb - ətraflı məlumat üçün [LICENSE](LICENSE) faylına baxın.

```
MIT License

Copyright (c) 2025 Taynur

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

## 👨‍💻 Əlaqə

**Taynur** - [@taynur2code](https://github.com/taynur2code)

Layihə Linki: [https://github.com/taynur2code/ecommerce](https://github.com/taynur2code/ecommerce)

---

<div align="center">
  
### 🌟 Layihəni bəyəndinizsə ulduz verməyi unutmayın!

**Hazırladı ❤️ ilə [Taynur](https://github.com/taynur2code)**

</div>


