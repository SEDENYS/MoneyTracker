



```markdown
# 💸 MoneyTracker

A simple **Monthly Spending Tracker** built with **HTML, CSS, and JavaScript**, designed to help you track and visualize your expenses by category and month.  
All data is stored in **LocalStorage**, so your progress stays saved even after you close the browser.

---

## 🚀 Features

- 🗓️ Select **month** and **year** to organize your expenses  
- 🧾 Add spending amounts for categories:
  - Housing  
  - Food  
  - Transportation  
  - Bills  
  - Miscellaneous  
- 💾 Data automatically saved to **LocalStorage**  
- 📊 Interactive **doughnut chart** using [Chart.js](https://www.chartjs.org/)  
- 📱 Responsive and minimalist UI design  

---

## 🧠 How It Works

1. Choose **Month**, **Year**, **Category**, and enter an **Amount**.
2. Press **Add Expense**.
3. Your expenses are saved and visualized in a colorful chart.
4. You can switch between months and years to view previous data.
5. Negative values can be used to adjust (subtract) an amount — but not below zero.

---

## 🧩 Technologies Used

| Stack | Description |
|-------|--------------|
| **HTML5** | Structure and form elements |
| **CSS3** | Responsive and clean styling |
| **JavaScript (Vanilla)** | App logic, LocalStorage, and Chart.js integration |
| **Chart.js v4** | Visual representation of expenses |
| **Font Awesome v7** | Icons and styling (optional) |

---

## 🗂️ Project Structure

```

MoneyTracker/
│
├── index.html          # Main HTML file
├── style.css           # Styling for layout and design
├── script.js           # App logic (expenses, chart, storage)
├── favicon.png         # App icon
└── README.md           # Project documentation

````

---

## ⚙️ Setup & Usage

1. Clone or download this repository:
   ```bash
   git clone https://github.com/SEDENYS/MoneyTracker.git
````

2. Open the folder and simply launch `index.html` in your browser.
3. Start tracking your monthly expenses instantly!

> 💡 No backend or installation needed — everything runs locally in the browser.

---

## 🧹 Data Storage

All expense data is saved automatically to the browser’s **LocalStorage** using a key format:

```
{Month}-{Year}
```

Example:
`January-2025` → `{ Housing: 1200, Food: 350, Transportation: 100, Bills: 200, Miscellaneous: 50 }`

To clear your data, open DevTools → Application → LocalStorage and remove the entries manually.

---

## 🧠 Future Improvements (Ideas)

* 💬 Add total monthly summary and progress bars
* 🔐 Sync data to cloud or user account
* 💱 Add multi-currency support
* 📅 Export to CSV / Excel
* 📈 Include income tracking and balance visualization

---

## 🧑‍💻 Author

**Denys Semenets**
📍 Toronto, Canada
💼 GitHub: [@SEDENYS](https://github.com/SEDENYS)

---

## 🪙 License

This project is licensed under the **MIT License** — free to use, modify, and share.

---

> “Track your spending, understand your habits, and make smarter financial decisions.” 💡


