# ⚽ Football Data Analysis with Python, SQL, Excel & Tableau


> 📊 **Data-driven football insights for performance, scouting, fan engagement, and strategic decisions**

---

## 📌 Project Title
### **Decoding Football with Data**

🎓 **By:** Kathiravan P  
 

---

## 🧾 Description

This project explores a rich football dataset to uncover hidden patterns in player performance, team comparisons, attendance trends, referee behavior, substitution strategy, and more.

We used **Python, MySQL, Excel, and Tableau** to:
- Predict player goals and heights
- Analyze team and player performance
- Understand stadium, referee, and event impacts
- Segment players using machine learning
- Identify urgent contract decisions

---

## 🛠️ Tools & Technologies

| Tool       | Purpose                        |
|------------|--------------------------------|
| 🐍 Python  | Data cleaning, modeling (Logistic, Linear, KNN) |
| 🧮 MySQL   | Querying and storing structured data |
| 📊 Tableau | Dashboards and interactive visualizations |
| 📗 Excel   | Initial exploration and summary statistics |

---

## 📊 Key Analyses & Results

### 🔸 1. Goal Prediction Model (🎯 Accuracy: 86%)
- **Model**: Logistic Regression  
- **Features**: Minutes played, Position, Captain, Competition  


---

### 🔸 2. Central Limit Theorem Validation
- Random sampling proves **sample means follow normal distribution**
- Sample mean ≈ Population mean ✅

---

### 🔸 3. Player Height Prediction (📏 R² Score: 0.66)
- **Model**: Linear Regression  
- Predict height based on physical & performance stats

---

### 🔸 4. Team Comparison - ANOVA
- **Hypothesis**: Team height difference is significant  
- ✅ Null hypothesis rejected → Height varies across top teams

---

### 🔸 5. KNN Goal Range Prediction (📈 AUC: 0.82)
- Predict if a stadium is **high or low scoring**
- Features: Stadium, Competition

---

### 🔸 6. Hypothesis Testing
| Test Type | Finding |
|-----------|---------|
| T-Test | No major difference in goals: Weekend vs Weekday |
| Z-Test | Tall players don't score significantly more goals |

---

### 🔸 7. K-Means Clustering (k=4)
- Segmented players based on **age, country, value**
- ✅ Silhouette Score: `0.796`


---

### 🔸 8. Referee Behavior
- **Felix Zwayer** issued the most yellow cards (76)  
- Longer matches = More cards  
- Diversity across stadiums = Fair match control

---

### 🔸 9. Substitution Patterns
- Most frequent: **Attackers**  
- Peak times: `45-60 min` and near `90 min`  
- **Pulisic** substituted most (826 times)

---

### 🔸 10. Attendance & Stadium Insights
- **Signal Iduna Park** → Highest goals  
- **Santiago Bernabéu** → Highest avg. attendance  
- Weekend matches draw slightly more crowd

---

### 🔸 11. Contract & Market Value Analysis
- **Christian Pulisic** = Highest market value  
- Key contracts (9) expiring in **2024** – Needs renewal  
- Left-Back & Defensive Midfield = Future shortages

---

## 💼 Business Impact

- 🧠 **Smarter scouting** using goal/height prediction
- ⚖️ **Fair officiating** through referee trend tracking
- 💸 **Better investments** by analyzing player value vs. performance
- 📅 **Timely contract renewals** to avoid talent loss
- 📢 **Marketing insights** from attendance and fan behavior

---


---

## 📁 Folder Structure (Suggested)
📁 Football-Data-Analysis
├── 📂 data
├── 📂 notebooks
├── 📂 images
├── 📂 sql
├── 📂 tableau
├── README.md
└── requirements.txt

---

## 🚀 How to Run the Project

1. Clone this repo  
2. Set up environment with: `pip install -r requirements.txt`  
3. Run Jupyter notebooks  
4. Open Tableau dashboards from the `tableau/` folder

---




