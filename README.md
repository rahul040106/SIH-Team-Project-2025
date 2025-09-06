# 🏭 Vendor Inspection Report System

A web-based inspection reporting system built with **Flask** that tracks vendor product quality, warranty failures, inspection history, and provides vendor performance insights.  

It allows users to:
- View detailed inspection reports for individual items  
- Track vendor-wise inspection history  
- Detect early failures (before warranty expiry)  
- Compare alternative vendors for the same product  
- Calculate vendor quality scores  

---

## 🚀 Features

- **Vendor Quality Dashboard**  
  - Displays total products, failures, and overall quality score.  
- **Inspection Report Pages**  
  - Detailed item inspection history  
  - Highlighted failures within warranty  
- **Vendor History**  
  - Shows all past inspections for a vendor  
- **Alternative Vendor Suggestions**  
  - Compare performance of other vendors supplying the same product  
- **Responsive UI**  
  - Clean card layout with mobile-friendly design  

---

## 🛠️ Tech Stack

- **Backend:** Python, Flask  
- **Database:** SQLite (can be replaced with MySQL/PostgreSQL)  
- **Frontend:** Jinja2 templates, HTML5, CSS3  
- **Visualization:** Scorecards & tables  

---

## 📂 Project Structure

```
├── app.py              # Flask application
├── templates/
│   ├── index.html      # Home page
│   ├── report.html     # Inspection report template
│   └── base.html       # (Optional) Layout file
├── static/
│   └── style.css       # Custom styles (optional, inline CSS also used)
├── data/
│   └── inspection.db   # SQLite database (sample data)
└── README.md           # Documentation
```

---

## ⚡ Installation & Setup

1. **Clone repo**
   ```bash
   git clone https://github.com/your-username/vendor-inspection-system.git
   cd vendor-inspection-system
   ```

2. **Create virtual environment**
   ```bash
   python -m venv venv
   source venv/bin/activate   # Mac/Linux
   venv\Scripts\activate      # Windows
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run Flask app**
   ```bash
   flask run
   ```
   App runs at 👉 `http://127.0.0.1:5000/`

---

## 📝 Usage

- Go to the home page (`/`)  
- Enter an **Item ID** to view its inspection report  
- Check:  
  - Vendor details  
  - Inspection history  
  - Early failures within warranty  
  - Vendor performance score  
  - Alternative vendors  

---

## 📸 Screenshots

> *(Add your screenshots here, e.g. report page, vendor quality score, early failure detection)*  

---

## 📌 Future Improvements

- Graphical charts for inspection results  
- Role-based access control (Admin, Inspector, Vendor)  
- Export reports to PDF/Excel  
- API endpoints for integration  

---

## 🤝 Contributing

1. Fork repo  
2. Create feature branch (`git checkout -b feature-name`)  
3. Commit changes (`git commit -m "Added feature"`)  
4. Push branch (`git push origin feature-name`)  
5. Open Pull Request  

---

## 📜 License


