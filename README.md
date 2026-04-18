# 🏏 CSK vs SRH — Match Prediction Page

A fun, interactive IPL match prediction web page for the **Chennai Super Kings vs Sunrisers Hyderabad** clash on **April 18, 2026** at Rajiv Gandhi International Stadium, Hyderabad.

---

## 📸 Preview

> A vibrant yellow-to-red gradient page featuring team logos, match details, and a live fan poll.

---

## 🚀 Features

- 🎨 **Team showcase** — Displays CSK and SRH team images side by side
- 📅 **Match info** — Date, time (7:30 PM), and venue details
- 📊 **Fan Poll** — Vote for your team and see live percentage results update in real time
- 📱 **Responsive design** — Works on mobile, tablet, and desktop screens

---

## 🗂️ Project Structure

```
project/
│
├── csk.html          # Main HTML file
└── images/
    ├── image.png       # CSK team image
    ├── srh.png         # SRH team image
    ├── match.png       # Match banner/logo
    └── prediction.jpeg # Match prediction graphic
```

---

## 🛠️ How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/Shanthi-Krishna-2709/csk-vs-srh.git
   ```

2. **Navigate to the project folder**
   ```bash
   cd csk-vs-srh
   ```

3. **Add your images** into the `images/` folder:
   - `image.png` — CSK logo/image
   - `srh.png` — SRH logo/image
   - `match.png` — Match center graphic
   - `prediction.jpeg` — Prediction banner

4. **Open `index.html`** in your browser — no server or installation needed!

---

## 🗳️ Poll Functionality

The poll lets fans vote for either CSK 💛 or SRH 🧡. After each vote:
- The progress bars update dynamically
- Percentages are recalculated and displayed in real time
- Built with pure vanilla JavaScript — no libraries needed

> **Note:** Poll votes reset on page refresh (no backend/storage).

---

## 🧰 Technologies Used

| Technology | Usage |
|------------|-------|
| HTML5 | Page structure |
| CSS3 | Styling & responsive layout |
| JavaScript (Vanilla) | Poll vote logic |

---

## 📱 Responsive Breakpoints

| Screen Size | Layout |
|-------------|--------|
| Desktop (>900px) | Side-by-side images |
| Tablet (600–900px) | Slightly stacked |
| Mobile (<600px) | Fully stacked, single column |

---

## 🤝 Contributing

Feel free to fork this repo and add features like:
- Backend vote persistence
- Player stats section
- Countdown timer to match start
- Share to social media button

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

> Made with 💛 for CSK fans and 🧡 for SRH fans — may the best team win! 🏆
