# 🏎️ Predict Lap Times 🕒

This project is designed to predict lap times for Formula 1 cars during free practice sessions, aiming to estimate race pace based on historical data. For this specific implementation, I captured **Lewis Hamilton's** lap times 🏁, using them as the dataset for the analysis and predictions. This project was just a fun little experiment to gain some insight into python and different technologies that are used! 

⚠️ **Note:** The predictions are not entirely accurate or reflective of real-life scenarios, as many variables (like track conditions, fuel loads, tire degradation, etc.) aren't accounted for in this simplified model.

---

## ✨ Features

- 🔍 Predict Formula 1 lap times based on historical data.
- 🧮 Basic data processing and analysis.
- 🚀 Developed and executed in **Google Colab**.

---

## 🛠️ Setup

### 📋 Prerequisites

- Install the required libraries, such as `pandas` and `numpy`. You can install them using:
  ```bash
  pip install pandas numpy
  ```

### 📂 Data Structure

Ensure you have a CSV file in the following format for the project to work. The file should be named `your_file_name.csv` and saved in the appropriate directory.

**Correct CSV Format:**

```
Lap,Time
1,01:12.123
2,01:12.430
3,01:11.820
4,01:11.952
5,01:12.268
6,01:11.915
7,01:12.029
8,01:12.175
9,01:11.753
```

📂 Save the CSV file in a folder and ensure the path is referenced correctly in the code:
```python
data = pd.read_csv('/content/your_file_name.csv')
```

---

## ▶️ Running the Project

1. 🔧 Open the Jupyter Notebook (`.ipynb`) in Google Colab or a local Jupyter environment.
2. 📤 Make sure the CSV file (`our_file_name.csv`) is uploaded to the correct location in your directory structure.
3. 🚦 Run the cells in the notebook sequentially to perform data analysis and prediction.

---

## 📝 Notes

- 🧑‍💻 This project is primarily for educational purposes.
- 🌐 It was developed in **Google Colab** and saved as a **Jupyter Notebook**.
- 📉 The dataset is limited and may not fully reflect the complexities of real-world Formula 1 lap time predictions.
