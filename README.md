# 📋 SkillBridge Student Feedback Form

A student freelancer feedback form for the **SkillBridge** platform — built to collect insights from students about their freelancing experiences, preferences, and feature requests.

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Visit%20Site-blue?style=for-the-badge)](https://muhammadhasnain1-debug.github.io/submit-form/)
[![GitHub Pages](https://img.shields.io/badge/Hosted%20on-GitHub%20Pages-181717?style=for-the-badge&logo=github)](https://muhammadhasnain1-debug.github.io/submit-form/)

---

## 🖼️ Preview

> The form is live at: **https://muhammadhasnain1-debug.github.io/submit-form/**

The form features a clean, modern design with a purple-to-blue gradient background and collects:
- Personal information (name, email, education level, field of study)
- Freelancing experience and platforms used
- Feature preferences and work style preferences
- Open-ended feedback and suggestions
- A star rating for likelihood to use the platform
- Interest in contributing to the SkillBridge team

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| **HTML5** | Page structure and form elements |
| **CSS3** | Styling, gradients, responsive layout |
| **JavaScript (Vanilla)** | Client-side form validation |
| **[FormSubmit.co](https://formsubmit.co)** | Serverless form submission (no backend needed) |
| **Font Awesome 6** | Icons throughout the UI |
| **GitHub Pages** | Free static site hosting |

---

## ⚙️ How It Works

1. **User fills out the form** — covering personal info, freelancing background, feature preferences, and feedback.
2. **Client-side validation** runs on submit — required fields are checked and errors are shown inline.
3. **FormSubmit.co handles the POST** — the form data is sent to the configured email address without any server-side code.
4. **User is redirected** to [`thankyou.html`](thankyou.html) after a successful submission.

---

## 📁 Project Structure

```
submit-form/
├── index.html       # Main feedback form
├── thankyou.html    # Post-submission thank-you page
└── README.md        # Project documentation
```

---

## 🚀 Running Locally

No build step required — just open `index.html` in your browser:

```bash
git clone https://github.com/MuhammadHasnain1-debug/submit-form.git
cd submit-form
open index.html   # macOS
# or double-click index.html in your file explorer
```

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
