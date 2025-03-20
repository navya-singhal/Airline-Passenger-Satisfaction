# ✈ Airline Passenger Satisfaction Prediction

## **Project Overview**
This project analyzes a **passenger satisfaction dataset** from a US airline to predict whether travelers are satisfied or dissatisfied. Using **machine learning models**, we identify key factors that impact satisfaction and propose actionable insights for airlines to enhance customer experience.

### **Goal**
To develop a **classification model** that predicts passenger satisfaction based on **travel experience, demographics, and flight details**.

---

## **Dataset**
The dataset contains **129,880 records** with features categorized as:

- **Passenger Information:** Age, gender, travel type, class of travel
- **Service Ratings:** Inflight Wi-Fi, seat comfort, online booking experience, food & beverage quality
- **Flight Characteristics:** Departure/arrival delays, baggage handling, flight distance

**Data Source:** [Kaggle - Airline Passenger Satisfaction](https://www.kaggle.com/datasets/teejmahal20/airline-passenger-satisfaction)

---

## **Methodology**

### **Data Preprocessing & Feature Engineering**
- **Handled Missing Data:** Imputed missing values for arrival delays.
- **Created New Features:** Introduced **average delay metric** to combine departure and arrival delays.
- **Categorical Encoding:** Converted text-based features (e.g., class, gender) into machine-readable format.
- **Feature Selection:** Identified **high-impact factors** using correlation analysis.

### **Model Selection & Training**
We tested multiple classification models:
| Model                     | Accuracy | Precision | Best Feature |
|---------------------------|----------|------------|---------------|
| **Naïve Bayes**           | 88%      | 89%        | Travel class |
| **K-Nearest Neighbors**   | 92%      | 91%        | Online boarding |
| **Logistic Regression**   | 87%      | 85%        | Inflight Wi-Fi |
| **Random Forest**         | 96%      | 97%        | Online boarding |
| **Gradient Boosting**     | 95%      | 96%        | Loyalty program |

**Best Model:** **Random Forest** (96% accuracy, 97% precision)

---

## **Key Findings**
- **Online boarding, inflight Wi-Fi, and loyalty programs drive satisfaction.**  
- **Personal travelers in economy class are more likely to be dissatisfied.**  
- **Flight delays impact economy travelers more than business travelers.**  
- **Satisfaction increases significantly for business class passengers.**  

---

## **Future Improvements**
- **Integrate real-time flight pricing & promotions** to evaluate price perception impact.  
- **Perform post-COVID travel analysis** to compare satisfaction trends.  
- **Apply deep learning models** (LSTMs, CNNs) for text-based review analysis.  
- **Use advanced NLP techniques** to analyze customer feedback for service improvements.  

---

## **How to Use This Repository**
### **Clone the repository**
```bash
git clone https://github.com/your-username/airline-passenger-satisfaction.git
cd airline-passenger-satisfaction
```

### **Install dependencies**
```bash
pip install -r requirements.txt
```

### **Run Jupyter Notebook**
```bash
jupyter notebook Final_Project_Airline_Satisfaction.ipynb
```

---

## **Contributors**
- Navya Singhal
- Alex Parson
- Ammar Mustafa
- Isha Verma
- Theresa Sushil

---

**Repository Structure**

airline-passenger-satisfaction/
│── Final_Project_Airline_Satisfaction.ipynb  # Main ML model & analysis
│── train.csv  # Training dataset
│── test.csv  # Testing dataset
│── Airline Passenger Satisfaction_DS Project.pdf  # Detailed report
│── Airline Passenger Satisfaction (Group 1).pdf  # Supporting documentation
│── README.md  # Project overview & usage guide
└── requirements.txt  # Dependencies

---

### **Key Enhancements:**
- **More structured & professional format**
- **Includes installation & execution steps**  
- **Clearly defined dataset, methodology, and findings**  
- **Lists contributors**  
- **Future improvements & next steps**  

Let me know if you'd like any further modifications before uploading it! 🚀

