
# 📦 WhatsApp Website Chat Widget — Floating WhatsApp Button for Websites
### The easiest way to add a WhatsApp chat widget to your website

A lightweight, customizable WhatsApp chat widget for modern websites and web apps. Add a floating WhatsApp button, customize colors and messages, and let visitors contact you instantly.  
Works with **React**, **Next.js**, **TanStack Start**, **Vue**, **Svelte**, **Astro**, and plain **HTML**.

---

## 🚀 Features
- Floating WhatsApp chat button  
- Fully customizable (colors, message, size, position)  
- Zero dependencies  
- Mobile‑friendly  
- Works with all frameworks  
- TypeScript support  
- SEO‑friendly and lightweight  

---

## 📥 Installation

```bash
npm install whatsapp-website-chat-widget
# or
yarn add whatsapp-website-chat-widget
# or
pnpm add whatsapp-website-chat-widget
```

---

## 🧩 Usage (React Example)

```tsx
import { WhatsAppWidget } from "whatsapp-website-chat-widget";

export default function App() {
  return (
    <WhatsAppWidget
      phone="+1234567890"
      message="Hello! I need help"
      position="right"
      color="#25D366"
      size={56}
    />
  );
}
```

---

## 🌐 Usage (HTML / Vanilla JS)

```html
<script src="https://unpkg.com/whatsapp-website-chat-widget"></script>

<script>
  WhatsAppWidget.init({
    phone: "+1234567890",
    message: "Hello!",
    position: "right",
    color: "#25D366",
  });
</script>
```

---

## ⚙️ Configuration Options

| Option | Type | Default | Description |
|--------|------|---------|-------------|
| `phone` | string | required | WhatsApp phone number (international format) |
| `message` | string | `""` | Prefilled message when chat opens |
| `position` | `"left"` \| `"right"` | `"right"` | Widget position on screen |
| `color` | string | `"#25D366"` | Button background color |
| `size` | number | `56` | Button diameter in pixels |

---

## 📸 Screenshots  
*(Add your widget screenshots here — Google ranks README images highly)*

Example placeholders:

```
/screenshots/widget-light.png
/screenshots/widget-dark.png
```

---

## 🛠️ Framework Integrations

This widget works out of the box with:

- React  
- Next.js  
- TanStack Start  
- Vue  
- Svelte  
- Astro  
- SolidJS  
- Plain HTML  

If you want, I can generate **framework‑specific examples** for each one.

---

## 📈 Why Use a WhatsApp Chat Widget?

Adding WhatsApp to your website improves:

- Customer support response time  
- Conversion rates  
- Trust and accessibility  
- Mobile engagement  
- Lead generation  

Users prefer WhatsApp because it’s familiar, fast, and frictionless.

---

## 🔧 Development

```bash
git clone https://github.com/alexasomba/whatsapp-website-chat-widget
cd whatsapp-website-chat-widget
npm install
npm run dev
```

---

## 🧪 Testing  
*(Optional — add if you plan to include tests)*

---

## 📦 Publishing (for maintainers)

```bash
npm run build
npm publish
```

---

## 🗺️ Roadmap
[x] Dark mode auto‑detection  
[x] Multi‑agent support  
[] WhatsApp Business API integration  
[] Analytics dashboard  
[] Custom icons  

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!  
Feel free to open a PR or issue.

---

## 📄 License

MIT — free to use, modify, and distribute.

---

## ⭐ Support the Project

If this widget helps you, consider giving the repo a **star** on GitHub. It helps visibility and encourages continued development.
