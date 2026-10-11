# 💍 Bandhan.com - Modern Matrimonial Web Platform

<p align="center">
  <img src="Frontend/img1.jpg" alt="Bandhan Banner" width="700" style="border-radius: 12px; box-shadow: 0 8px 24px rgba(0,0,0,0.15);" />
</p>

<p align="center">
  <strong>Find Your Perfect Soulmate & Meaningful Connections</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/Font_Awesome-528DD7?style=for-the-badge&logo=font-awesome&logoColor=white" alt="Font Awesome" />
  <img src="https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge" alt="Status" />
</p>

---

## 📖 Overview

**Bandhan.com** is an intuitive, responsive, and aesthetically pleasing Matrimonial web platform designed to simplify the journey of matchmaking. It empowers users to explore verified profiles, craft customized matrimonial biodatas, express interest, and manage personal preferences effortlessly with a clean, contemporary user interface.

---

## ✨ Features

- **🏠 Interactive Landing Page (`index.html`)**
  - Hero banner with quick match search filter (Gender, Age range, Religion, Mother Tongue).
  - Featured bride & groom profiles showcase.
  - "How It Works" step-by-step guidance.
  - Testimonials & Success Stories section.

- **🔐 Authentication & User Onboarding**
  - **Signup (`signup.html`)**: Multi-field registration flow with role selection (Creating for Self, Son, Daughter, Brother, Sister, Friend).
  - **Login (`login.html`)**: Secure, user-friendly authentication with credential remembering & password recovery shortcuts.
  - **Logout (`logout.html`)**: Graceful session termination with redirect confirmation.

- **📊 Comprehensive User Dashboard (`dashboard.html`)**
  - Quick metrics overview (Profile views, Interests received/sent, Matches found).
  - Activity stream and profile completeness tracker.
  - Direct quick navigation sidebar to matches, profile, and interests.

- **👤 In-Depth Profile Management (`myprofile.html`)**
  - Personal, Religious, Educational, and Professional details.
  - Horoscope & Astrological background (Rashi, Nakshatra, Manglik status).
  - Lifestyle preferences, hobbies, and family background.

- **📄 Matrimonial Biodata Generator & Viewer (`biodata.html`)**
  - Formatted, printable, and shareable standard matrimonial biodata layout.
  - Clean typographic hierarchy structured for families and traditional matchmaking.

- **🔍 Potential Matches Discovery (`potentialmatches.html`)**
  - Smart filter controls (Age, Religion, Caste, State/City, Occupation).
  - Interactive profile cards with "Send Interest", "Shortlist", and "View Full Profile" actions.

- **💌 Interest Tracking (`myInterest.html`)**
  - Categorized management of connections:
    - *Accepted Interests*
    - *Pending Requests*
    - *Received Interests*

- **ℹ️ Informational Pages**
  - **About Us (`about.html`)**: Company vision, core values, and matchmaking ethos.
  - **Contact Us (`contact.html`)**: Support enquiry form, office addresses, helpline numbers, and FAQs.

---

## 🗂️ Project Structure

```text
Matrimonial Web/
├── Frontend/
│   ├── about.html             # About Us page
│   ├── biodata.html           # Matrimonial biodata template/viewer
│   ├── contact.html           # Contact Us & support page
│   ├── dashboard.html         # User dashboard & activity hub
│   ├── img1.jpg               # Visual assets / Hero banner
│   ├── index.html             # Main landing & discovery page
│   ├── login.html             # User login page
│   ├── logout.html            # Session logout confirmation
│   ├── myInterest.html        # Sent/Received interest management
│   ├── myprofile.html         # User profile view & edit page
│   ├── potentialmatches.html  # Search & browse potential matches
│   └── signup.html            # New user registration page
├── .gitignore                 # Git ignore rules
└── README.md                  # Project documentation
```

---

## 🚀 Getting Started

No build tools or server setup are strictly required—Bandhan is built using vanilla web technologies and runs right out of the box.

### Prerequisites

- Any modern web browser (Google Chrome, Mozilla Firefox, Microsoft Edge, Safari).
- *(Optional)* A local HTTP server or VS Code Live Server extension for enhanced local development.

### Running Locally

1. **Clone the repository:**
   ```bash
   git clone https://github.com/paraspatil31/matrimonial-site-.git
   cd matrimonial-site-
   ```

2. **Open directly in browser:**
   Double click on `Frontend/index.html` or open it directly in your web browser.

   *Alternatively, run a simple local HTTP server:*
   ```bash
   # Using Python 3
   python -m http.server 8000
   ```
   Then navigate to: `http://localhost:8000/Frontend/`

---

## 🎨 Technology Stack

- **Markup**: [HTML5](https://developer.mozilla.org/en-US/docs/Web/HTML) with semantic tags
- **Styling**: [CSS3](https://developer.mozilla.org/en-US/docs/Web/CSS) (Custom CSS, Flexbox, Grid, CSS transitions)
- **Icons**: [Font Awesome 6.4.0](https://fontawesome.com/)
- **Typography**: Modern system fonts & Segoe UI

---

## 🔮 Future Enhancements

- [ ] Backend integration with RESTful API (Node.js/Express or Python/Django)
- [ ] Database support (MongoDB / PostgreSQL) for dynamic user and match records
- [ ] Real-time 1-on-1 chat and matchmaking messaging
- [ ] Photo gallery upload with privacy blur/lock controls
- [ ] Automated Kundali / Horoscope matching algorithm

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!
Feel free to check the [issues page](https://github.com/paraspatil31/matrimonial-site-/issues).

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information if applicable.

---

<p align="center">
  Crafted with ❤️ by <a href="https://github.com/paraspatil31">Paras Patil</a>
</p>
