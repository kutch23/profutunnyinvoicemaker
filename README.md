
🧾 PROFUTUNNY INVESTMENTS - Invoice Generator

A responsive, customizable invoice generator built with HTML, CSS, and JavaScript. Designed for PROFUTUNNY INVESTMENTS, this tool allows users to input company, customer, and invoice details, dynamically add items, and generate a professional invoice for printing or PDF export.

---

## 🚀 Features

- ✅ Responsive layout for desktop and mobile
- 🖼️ Logo upload or URL preview
- 🧮 Dynamic item rows with auto-calculated totals
- 🖨️ Print-ready formatting
- 📄 High-resolution PDF export using `html2canvas` and `jsPDF`
- 🧾 Pre-filled company and customer details
- 🔒 VAT and PO number support (customizable)

---

## 📁 File Structure

```plaintext
index.html         # Main application file
assets/            # (Optional) Folder for logo uploads or future assets
```

---

## 🛠️ Technologies Used

- HTML5 & CSS3
- Vanilla JavaScript
- [jsPDF](https://github.com/parallax/jsPDF)
- [html2canvas](https://github.com/niklasvh/html2canvas)

---

## 📦 How to Use

1. Open `index.html` in any modern browser.
2. Fill in company, customer, and invoice details.
3. Add invoice items using the **Add Item** button.
4. Click **Generate Invoice** to preview.
5. Choose to **Print** or **Save as PDF**.

---

## 🧰 Customization

- 💱 Change currency by replacing `"ZAR"` labels in HTML and JavaScript.
- 🧾 Add VAT or discounts by modifying the `calculateTotals()` function.
- 🌍 For multi-language support, wrap labels in a localization function.

---

## 🧪 Development Notes

- PDF export uses a cloned DOM element with increased scale for better resolution.
- Minimum one invoice item is required.
- VAT is currently set to 0% (can be adjusted in script logic).

---

## 👨‍💼 Author

Built for **PROFUTUNNY INVESTMENTS**  
Crafted by [Thembani] — blending technical precision with practical design for real-world business needs.

---

## 📜 License

This project is for internal use by PROFUTUNNY INVESTMENTS.  
For reuse or adaptation, please contact the author.

---

Let me know if you'd like a badge section, GitHub Pages deployment instructions, or a version tailored for clients or staff onboarding.
