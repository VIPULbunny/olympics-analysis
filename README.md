# 🏅 Olympics Data Analysis (1896-2016)
![image](https://images-cdn.ubuy.co.in/634fbb37ad83f63c086c2195-olympics-flag-olympic-games-yard-flags.jpg)


## 📌 Project Overview
The **Olympic Games** have been the pinnacle of international sports since **1896**. This project explores the historical dataset of the Olympics, uncovering trends, athlete performance, and country-wise participation. Through data cleaning, visualization, and analysis, we gain insights into how the Games have evolved over time.

## 📂 Dataset Description
The size of **athlete_events.csv** is more than 20mb so i had provided the link and description in the file name **'Dataset_link.py'**

This analysis uses two primary datasets:

1. **athlete_events.csv** - Contains detailed records of Olympic athletes, including:
   - Name, Age, Gender
   - Sport, Event, Medal (if won)
   - Country (NOC), Year, Season (Summer/Winter)

2. **noc_regions.csv** - Maps National Olympic Committees (NOCs) to country names, helping in regional analysis.

## 🚀 Project Objectives
- Perform **Exploratory Data Analysis (EDA)** to understand athlete trends.
- Visualize country-wise **medal counts** and athlete participation.
- Analyze **gender representation** and its evolution in the Olympics.
- Identify the **most successful athletes and countries** over the years.

## 🔧 Installation
To run this project on your local m  achine:

1. **Clone the Repository:**
   ```sh
   git clone https://github.com/VIPULbunny/olympics-analysis.git
   ```
2. **Navigate to the Project Directory:**
   ```sh
   cd olympics-analysis
   ```
3. **Install Dependencies:**
   ```sh
   pip install numpy pandas matplotlib seaborn
   ```
4. **Run the Jupyter Notebook:**
   ```sh
   jupyter notebook
   ```

## 📊 Exploratory Data Analysis (EDA)
### 🏆 Key Insights from Data
- **Total Athletes Participated:** `{total_athletes}`
- **Total Olympic Games Editions:** `{total_games}`
- **Top 10 Countries by Athlete Count:**
  - USA, Germany, UK, France, China, etc.
- **Most Successful Athletes:**
  - Michael Phelps, Usain Bolt, etc.
- **Gender Representation Over Time:**
  - Increasing female participation in modern Olympics.

### 🔎 Data Cleaning & Preprocessing
- Merged `athlete_events.csv` with `noc_regions.csv` for accurate country mapping.
- Handled **missing values** in age, medal, and region data.
- Converted categorical features (`Sex`, `Medal`) into structured formats for better analysis.

## 📈 Data Visualizations
### 🎖️ Medal Distribution
![image](https://github.com/user-attachments/assets/979e489f-84ef-4ec1-aff4-3b54ec167274)


### 🏅 Top 10 Countries by Medal Count
![image](https://github.com/user-attachments/assets/73ea54c6-360e-48e5-9738-9a93f48a8cee)


### 📊 Gender Representation Over the Years
![image](https://github.com/user-attachments/assets/bd1dc1b6-aa44-419c-8fca-36c781230c2e)

### 🌍  Count occurrences of 'Sex' for each 'Season'
![image](https://github.com/user-attachments/assets/61806be5-16fa-4cca-9e22-ade7da9a11bc)


## 📜 License
This project is licensed under the **MIT License**.

## 🤝 Contributing
We welcome contributions! If you’d like to improve the analysis or add new insights:

1. **Fork the repository**.
2. **Create a feature branch**: `git checkout -b feature-branch`
3. **Commit your changes**: `git commit -m "Added new analysis"`
4. **Push to GitHub**: `git push origin feature-branch`
5. **Open a Pull Request** 🚀

## 📬 Contact
For queries or collaborations, reach out via email or open an issue on GitHub.

---
**⭐ If you find this project useful, please give it a star!** 🌟

