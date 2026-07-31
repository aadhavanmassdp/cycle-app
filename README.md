# Suriyadev Cycles – Premium Bicycles E‑Commerce Platform

A complete single‑page application (SPA) for an online bicycle store, built with vanilla JavaScript, Bootstrap 5, and a clean, modern UI. The platform includes user authentication (email + OTP), dynamic product filtering/sorting, a QR‑code‑based payment simulation, and a responsive design that works on all devices.

---

## 🚀 Live Demo

> [Open the live site](#) – *replace with your hosted URL*

---

## 📦 Features

| Feature | Description |
|---------|-------------|
| **User Authentication** | Register / Login with email and 6‑digit OTP verification. OTPs are generated and validated client‑side for demonstration. |
| **Product Catalog** | 12 sample bicycles across 5 categories (Road, Mountain, Electric, Hybrid, Kids). Each product has a name, price, rating, stock status, and image. |
| **Dynamic Filtering** | Filter by category, sort by price (low‑high / high‑low) or rating, and set a minimum rating using a slider. Results update in real‑time. |
| **QR Payment Simulation** | Clicking “Add to Cart” opens a modal with a scannable QR code (linked to a sample payment URL). A “Payed” button simulates successful payment. |
| **Featured Bikes** | Homepage showcases 4 featured products with quick “Add to Cart” buttons. |
| **Responsive Design** | Built with Bootstrap 5 and custom CSS, the layout adapts smoothly from desktop to mobile. |
| **Blog Section** | Highlights the platform’s core values: security, scalability, and user‑centric design. |
| **Newsletter Subscription** | Footer includes a subscribe button with a simple alert confirmation. |

---

## 🎨 Color Palette

The UI follows a cohesive blue‑themed palette:

| Color Name | Hex Code | Usage |
|------------|----------|-------|
| White      | `#ffffff` | Backgrounds, cards, navbar |
| Bright Blue| `#00a7e1` | Primary buttons, links, accents |
| Dark Navy  | `#00171f` | Headings, primary text |
| Deep Blue  | `#003459` | Secondary text, subtle elements |
| Ocean Blue | `#007ea7` | Category labels, muted text, footer links |

---

## 🛠️ Tech Stack

- **HTML5** – Semantic markup
- **CSS3** – Custom styles + Bootstrap 5.3
- **JavaScript (Vanilla ES6)** – All app logic, DOM manipulation, and event handling
- **Bootstrap Icons** – Icon library
- **QRCode.js** – Generates QR codes inside the payment modal
- **Google Fonts (Inter)** – Modern, clean typography

---

## 📁 Project Structure

```
suriyadev-cycles/
│
├── index.html          # Single HTML file containing all markup, styles, and scripts
├── README.md           # This file
└── assets/             # (optional) – images, additional assets
```

> **Note:** The entire application is contained in one HTML file for simplicity and easy deployment.

---

## 🔧 Setup & Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/suriyadev-cycles.git
   cd suriyadev-cycles
   ```

2. **Open the file**
   - Simply open `index.html` in your favourite browser.
   - No build tools, server, or dependencies are required – everything is loaded from CDNs.

3. **Customise (optional)**
   - Update the product array inside the `<script>` tag to add/remove bicycles.
   - Change the QR code URL (`https://q.me-qr.com/vks4u37k`) to your own payment link.
   - Modify the color palette in the `<style>` section to match your brand.

---

## 🧑‍💻 How It Works

### Authentication Flow
1. **Register** – Fill in name, email, password, and confirm password. Click “Send OTP” – a 6‑digit code is generated and displayed in an alert. Enter the code and click “Verify”. Once verified, the Register button becomes active.
2. **Login** – Enter your email, click “Send OTP”. A modal appears with the generated code. Enter the code and verify. After verification, the “Sign In” button is enabled.
3. **Session** – After successful login/registration, the navbar updates to show the user’s email and a “Logout” button.

### Product Filtering & Sorting
- **Category** – Filters products by type.
- **Sort** – Orders results by price (ascending/descending) or rating.
- **Rating Slider** – Shows only products with a rating equal to or higher than the selected value.
- All filters work together; results update instantly.

### QR Payment Simulation
- Click **“Add to Cart”** on any product.
- A modal opens with a QR code (static link for demo purposes).
- Click **“Payed”** – the button changes to “Confirmed!”, a success message appears, and the modal auto‑closes after 1.5 seconds.

---

## 📱 Responsive Breakpoints

| Breakpoint | Devices |
|------------|---------|
| ≥ 1200px   | Large desktops |
| ≥ 992px    | Desktops, laptops |
| ≥ 768px    | Tablets, small laptops |
| ≥ 576px    | Large phones |
| < 576px    | Small phones (portrait) |

The layout stacks vertically on smaller screens, and touch targets are sized appropriately.

---

## 🔒 Security Notes

- This is a **frontend‑only** demo. OTPs are generated and verified client‑side.
- For production, you would:
  - Send OTPs via a real email/SMS service (e.g., Twilio, SendGrid).
  - Hash passwords and store user data securely on a backend.
  - Replace the static QR URL with a dynamic payment gateway integration.

---

## 🤝 Contributing

Contributions are welcome! If you find a bug or have a suggestion:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Make your changes and commit (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Open a Pull Request.

---

## 📄 License

This project is open‑source and available under the **MIT License**. You are free to use, modify, and distribute it for personal or commercial purposes.

---

## 🙌 Acknowledgements

- [Bootstrap](https://getbootstrap.com/) – CSS framework
- [QRCode.js](https://github.com/davidshimjs/qrcodejs) – QR code generation
- [Unsplash](https://unsplash.com/) – Product images (used for demonstration)
- [Google Fonts](https://fonts.google.com/) – Inter font family

---

## 📬 Contact

**Suriyadev Cycles**  
Email: aadthiyaa@gmail.com  
GitHub: [@your-username](https://github.com/your-username)

---

> Built with ❤️ for riders everywhere.
