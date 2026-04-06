# 🧾 SoloInvoice (MicroBill)
### Free · Offline · Professional PDF Invoice Generator

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Made in India](https://img.shields.io/badge/Made%20in-India%20🇮🇳-orange)](https://avinashwalton.github.io/SoloInvoice)
[![Live Demo](https://img.shields.io/badge/Live-Demo-blue)](https://avinashwalton.github.io/SoloInvoice)
[![No Server](https://img.shields.io/badge/Server-None%20(Offline)-lightgrey)](https://avinashwalton.github.io/SoloInvoice)
[![Zero Cost](https://img.shields.io/badge/Cost-Free%20Forever-brightgreen)](https://avinashwalton.github.io/SoloInvoice)

> Create beautiful, professional PDF invoices instantly — right in your browser. No login, no monthly fee, no server, no data collection. **Forever free.**

🌐 **Live App:** [avinashwalton.github.io/SoloInvoice](https://avinashwalton.github.io/SoloInvoice)

---

## ✨ Features

| Feature | Details |
|---|---|
| 📄 **PDF Generation** | One-click PDF via browser's built-in print-to-PDF (zero dependency) |
| 🔒 **100% Offline** | Works without internet. Your data never leaves your browser |
| 💾 **LocalStorage Save** | Save multiple invoices and reload them anytime |
| 🏢 **Business Profile** | Save your company info once — auto-loads every time |
| 🖼️ **Logo Upload** | Add your company logo (PNG, JPG, SVG, max 2MB) |
| ✍️ **Signature Upload** | Upload your handwritten signature image — appears on every invoice above the signatory name |
| 📦 **Line Items** | Add unlimited services/products with qty, rate, auto-total |
| 🧮 **Tax & Discount** | GST/tax %, discount %, shipping charges — all auto-calculated |
| 💱 **Multi-Currency** | INR ₹, USD $, EUR €, GBP £, JPY ¥, AUD A$, AED د.إ |
| 🏦 **Bank Details** | Bank name, A/C number, IFSC code, UPI ID on invoice |
| 🖨️ **Print Ready** | Opens clean invoice-only print window — no form, no UI noise |
| 📤 **Share Link** | Share app link via Web Share API or clipboard copy |
| 🎨 **Color Themes** | Pick accent colors for your invoice branding |
| 📱 **Responsive** | Works perfectly on mobile, tablet, and desktop |
| 🔖 **Payment Stamp** | Auto PAID / UNPAID / OVERDUE / PENDING stamp on invoice |

---

## 🚀 Quick Start

### Option 1 — Use Online (Recommended)
Just visit 👉 [avinashwalton.github.io/SoloInvoice](https://avinashwalton.github.io/SoloInvoice)

### Option 2 — Run Locally
```bash
git clone https://github.com/AvinashWalton/SoloInvoice.git
cd SoloInvoice
open index.html   # Just open in any browser — no build step needed!
```

No npm install. No build step. No dependencies. Single HTML file.

---

## 📁 Project Structure

```
SoloInvoice/
├── index.html       # The entire app — HTML + CSS + JS in one file
├── README.md        # This file
└── LICENSE          # MIT License
```

---

## 🛠️ Tech Stack

| Tech | Usage |
|---|---|
| **HTML5** | Semantic structure, SEO meta tags, Open Graph |
| **CSS3** | Custom properties, Grid, Flexbox, animations |
| **Vanilla JS** | All logic — zero frameworks, zero dependencies |
| **Browser Print API** | Client-side PDF via print-to-PDF (no CDN needed) |
| **localStorage** | Invoice and business data persistence |
| **FileReader API** | Logo & signature image upload (base64) |

Zero backend. Zero database. Zero cost.

---

## 📸 How to Use

### Step 1 — Set Up Your Business Profile
1. Click the **Business** tab
2. Enter your company name, tagline, email, phone, address, GSTIN, PAN
3. Upload your **company logo** (PNG/JPG/SVG)
4. Upload your **handwritten signature image** (PNG with transparent background works best)
5. Click **Save Business Info** — it auto-loads on every visit

### Step 2 — Create an Invoice
1. Go to the **Invoice** tab
2. Fill in invoice number, date, due date
3. Add client name, email, address, GSTIN
4. Add line items with description, quantity, rate
5. Set currency, tax %, discount % as needed
6. Add bank/UPI payment details
7. Add notes and payment terms

### Step 3 — Download / Print
- **Download PDF Invoice** → clean invoice window opens → select **"Save as PDF"** in print dialog → Save
- **Print** → same clean window opens directly for printing
- **Save Invoice** → saved to your browser's localStorage for future reference

---

## 🖨️ PDF Download — How it Works

SoloInvoice uses the browser's native **Print → Save as PDF** instead of a third-party library. This means:
- ✅ Works 100% offline — no CDN required
- ✅ No html2pdf or jsPDF dependency
- ✅ Pixel-perfect A4 output with all colors preserved
- ✅ Works on Chrome, Firefox, Edge, Safari

**When the print dialog opens:**
1. **Destination** → select `Save as PDF` or `Microsoft Print to PDF`
2. **Layout** → `Portrait`
3. Click **Save**

---

## 🗺️ Roadmap

- [ ] QR code for UPI payment on invoice
- [ ] Invoice email via mailto link
- [ ] Multiple invoice templates (Classic, Modern, Minimal)
- [ ] Dark mode
- [ ] CSV export of saved invoice list
- [ ] Recurring invoice support
- [ ] PWA / installable as offline app

---

## 🤝 Contributing

Contributions are welcome!
- 🐛 [Report bugs](https://github.com/AvinashWalton/SoloInvoice/issues)
- 💡 [Request features](https://github.com/AvinashWalton/SoloInvoice/issues)
- 🔧 Submit pull requests — just edit `index.html`

---

## 📄 License

MIT License — see [LICENSE](LICENSE) for details. Free to use, modify, and distribute.

---

## 👨‍💻 Author

**Avinash Walton**

[![YouTube](https://img.shields.io/badge/YouTube-@AvinashWalton-red?logo=youtube)](https://youtube.com/@AvinashWalton)
[![Twitter](https://img.shields.io/badge/Twitter-@AvinashWalton-1DA1F2?logo=twitter)](https://twitter.com/AvinashWalton)
[![Instagram](https://img.shields.io/badge/Instagram-@AvinashWalton-E4405F?logo=instagram)](https://instagram.com/AvinashWalton)
[![Facebook](https://img.shields.io/badge/Facebook-AvinashWalton-1877F2?logo=facebook)](https://facebook.com/AvinashWalton)
[![Threads](https://img.shields.io/badge/Threads-@AvinashWalton-000?logo=threads)](https://threads.net/@AvinashWalton)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-SonuKumarSuman-0077B5?logo=linkedin)](https://linkedin.com/in/SonuKumarSuman)
[![GitHub](https://img.shields.io/badge/GitHub-AvinashWalton-181717?logo=github)](https://github.com/AvinashWalton)

---

## 🛠️ Other Tools by Avinash Walton

| Tool | Description |
|---|---|
| [FileFlux](https://avinashwalton.github.io/fileflux) | File conversion and management |
| [AuthorPro](https://avinashwalton.github.io/AuthorPro) | Writing and authoring tool |
| [DesiLang](https://avinashwalton.github.io/DesiLang) | Indian language utilities |
| [TranscriptPro](https://avinashwalton.github.io/transcriptpro) | Transcript and subtitle tool |
| [PromptVault Pro](https://avinashwalton.github.io/PromptVaultPro/) | AI prompt library |
| [SanitizeOS](https://avinashwalton.github.io/SanitizeOS/) | System cleanup utility |
| [PixelLocker](https://avinashwalton.github.io/PixelLocker/) | Image privacy & security tool |

---

<p align="center">Made with ❤️ in India &nbsp;·&nbsp; <strong>Avinash Walton</strong></p>
