# KocakTech - Mobile App Development Studio

![KocakTech Logo](https://img.shields.io/badge/KocakTech-Mobile%20Apps-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Vercel](https://img.shields.io/badge/deployed%20on-Vercel-black)

Modern, responsive landing page for KocakTech - an independent mobile app development studio.

## 🌐 Live Demo

[https://KocakTech.vercel.app](https://KocakTech.vercel.app) - *Deploy edildiğinde link güncellenecek*

## ✨ Features

- 🎨 **Modern Design** - Dark mode technology aesthetic with blue-purple gradients
- 🌍 **Multi-language Support** - English and Turkish (EN/TR)
- 📱 **Fully Responsive** - Mobile-first design approach
- 🚀 **Fast Performance** - Optimized static site with CDN delivery
- 🎭 **Smooth Animations** - AOS scroll animations and hover effects
- 🔒 **Privacy Policy** - Dedicated privacy policy page
- ♿ **Accessibility** - Semantic HTML and keyboard navigation support

## 📱 Apps Portfolio

| App | Description | Status | Links |
|-----|-------------|--------|-------|
| **Saydım** | Countdown & special day tracking | ✅ Live | [App Store](https://apps.apple.com/tr/app/sayd%C4%B1m/id6759845082) |
| **Komiserim** | Police exam preparation | ✅ Live | [App Store](https://apps.apple.com/tr/app/komiserim-akademi-pro/id6759722501) · [Play Store](https://play.google.com/store/apps/details?id=com.komiserim.akademi) |
| **Arabam+** | Vehicle expense tracking | 🚧 Coming Soon | - |

## 🛠️ Tech Stack

- **HTML5** - Semantic markup
- **Tailwind CSS** - Utility-first CSS framework (via CDN)
- **JavaScript** - Vanilla JS for interactions
- **AOS** - Animate On Scroll library
- **Lucide Icons** - Modern icon library

## 🚀 Deployment

### Vercel (Önerilen)

1. GitHub repo'sunu Vercel'e bağlayın:
   ```bash
   # Vercel CLI ile
   npm i -g vercel
   vercel
   ```

2. Vercel Dashboard üzerinden:
   - [vercel.com](https://vercel.com)'e gidin
   - "New Project" tıklayın
   - GitHub repo'sunu seçin
   - Deploy edin

### Manuel Deploy

```bash
# Vercel CLI ile
vercel --prod
```

### GitHub Actions ile Otomatik Vercel Deploy

Repo artık `master` veya `main` dalına push geldiğinde production deploy çalıştırabilecek bir GitHub Actions workflow içerir:

- Workflow dosyası: `.github/workflows/vercel-production.yml`
- Gerekli repository secrets:
  - `VERCEL_TOKEN`
  - `VERCEL_ORG_ID`
  - `VERCEL_PROJECT_ID`

Bu secret'lar tanımlandığında workflow sırasıyla `vercel pull`, `vercel build --prod` ve `vercel deploy --prebuilt --prod` komutlarını çalıştırır.

## 📁 Project Structure

```
webreklam/
├── index.html          # Ana sayfa / Main page
├── privacy.html        # Gizlilik politikası / Privacy policy
├── vercel.json         # Vercel yapılandırması / Vercel config
├── README.md           # Proje dökümantasyonu / Documentation
└── .gitignore          # Git ignore dosyası / Git ignore file
```

## 🌐 Language Support

Site tam olarak iki dilde mevcuttur:

- **English** (🇬🇧)
- **Türkçe** (🇹🇷)

Dil tercihi localStorage'da saklanır ve sayfalar arasında senkronize çalışır.

## 📝 SEO & Meta Tags

- ✅ Meta descriptions
- ✅ Open Graph tags
- ✅ Semantic HTML structure
- ✅ Mobile viewport optimization

## 🎨 Design System

### Colors
- **Primary:** `#2563EB` (Blue)
- **Secondary:** `#7C3AED` (Purple)
- **Background:** `#020617` / `#0F172A` (Dark)
- **Accent:** Blue-Purple gradient

### Fonts
- **Primary:** Inter
- **Display:** Space Grotesk

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 📧 Contact

- Email: contact@KocakTech.studio
- Website: [KocakTech.studio](https://KocakTech.studio)

---

<p align="center">
  Made with ❤️ by KocakTech Team
</p>
