```markdown
# 🇧🇩 Bangla MCQ Formatter & Font Converter (MS Word Add-in)

A lightweight, powerful, and offline-ready Microsoft Word Add-in designed specifically for educators, question setters, and content creators working with **Bangla Multiple Choice Questions (MCQs)**. 

This tool automates question formatting, handles option randomization, and provides a smart bi-directional font converter between **Unicode** and **Bijoy (SutonnyMJ)** with intelligent protection for English text, punctuation, and brackets.

---

## ✨ Key Features

*   **📄 Normal MCQ Formatting:** Automatically structures raw text into professional MCQ formats, including proper numbering and alignment, complete with answers and explanations.
*   **📑 Smart MCQ Formatting:** Automatically moves answer keys and explanations to a separate page layout at the end of the document.
*   **🔀 Option Randomization:** Shuffles MCQ options (ক, খ, গ, ঘ) randomly while accurately tracking the correct answer keys.
*   **🔄 Smart Bi-Directional Font Converter:**
    *   **Unicode ➔ Bijoy:** Converts standard Unicode text into Bijoy encoding (SutonnyMJ) while keeping English words, numbers, and spacing precisely formatted in *Times New Roman*. Handles specific key mapping for 'ে' (e-kar) automatically based on character positioning.
    *   **Bijoy ➔ Unicode:** Converts legacy Bijoy text back to standard Unicode (Kalpurush) smoothly without breaking complex conjuncts (*juktoborno*).
*   **🛡️ Complete Offline Privacy:** Runs entirely locally inside your Word task pane without relying on external third-party AI APIs, eliminating quotas, internet dependency, or security risks.

---

## 🛠️ Tech Stack

*   **HTML5 / CSS3 / JavaScript (ES6)**
*   **Tailwind CSS** (for modern UI styling)
*   **Office.js** (Microsoft Word JavaScript API)

---

## 📦 Project Structure

```text
├── taskpane.html       # Main UI and core processing logic (Parser & Converter Engine)
├── manifest.xml        # Office Add-in manifest configuration file
└── README.md           # Project documentation

```

---

## 🚀 Installation & Sideloading (For Testing & Local Use)

To run and test this add-in locally in your Microsoft Word application:

1. **Clone or Download** this repository to your local machine.
2. Ensure you have your `manifest.xml` and `taskpane.html` properly linked (if hosting locally or via GitHub Pages).
3. **Sideload the Add-in in Microsoft Word:**
* Open **Microsoft Word** (either on the Web or Desktop app).
* Open a new blank document.
* Go to the **Insert** tab on the ribbon and choose **Add-ins** (or *Get Add-ins*).
* Select **Manage My Add-ins** -> **Upload My Add-in**.
* Browse and select the `manifest.xml` file from this repository.
* Click **Upload**.



The Bangla MCQ Formatter panel will now appear in your Word ribbon!

---

## 💡 How to Use

1. **Select Text:** Highlight the raw or unformatted MCQ text inside your Word document.
2. **Format Questions:** Click **Format Selected (Normal MCQ)** or **Format Selected (Smart MCQ)** to instantly clean and structure your exam paper.
3. **Convert Fonts:** Use the **Unicode ➔ Bijoy** or **Bijoy ➔ Unicode** buttons to instantly transform your document formatting while preserving English text styles and complex Bangla conjuncts.

---

## 🤝 Contributions & Support

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://www.google.com/search?q=../../issues).

---

## 📝 License

This project is open-source and available under the [MIT License](https://www.google.com/search?q=LICENSE).
