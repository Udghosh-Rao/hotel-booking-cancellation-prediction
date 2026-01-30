# Hotel Booking Cancellation Prediction

## 📌 Project Overview
This project predicts whether a hotel booking will be cancelled using machine learning techniques. The dataset is provided from a Kaggle competition and contains customer booking details such as lead time, room type, price, and special requests.

## 📂 Dataset Description
The dataset contains the following files:
- `train.csv` – Training dataset with features and target variable  
- `test.csv` – Test dataset without target variable  
- `sample_submission.csv` – Sample submission format  

### Key Features:
- adults: Number of adults  
- children: Number of children  
- weekends: Number of weekend nights  
- weekdays: Number of weekday nights  
- meal_type: Selected meal type  
- room_type: Room type selected  
- arrival: Arrival date  
- lead_time: Days between booking and arrival  
- segment: Booking segment type  
- repeat: Whether customer is a repeat guest  
- price: Average room price  
- requests: Number of special requests  
- booking_status: Target variable (1 = Cancelled, 0 = Not Cancelled)  

## ⚙️ Approach
1. Data loading and exploration  
2. Handling missing values and data cleaning  
3. Feature engineering (total guests, stay duration, price per guest)  
4. Encoding categorical variables  
5. Model training using Random Forest Classifier  
6. Model evaluation using accuracy and ROC-AUC  
7. Generating prediction file for Kaggle submission  

## 📊 Results
The model was evaluated using validation data and achieved good predictive performance.

## 🛠️ Technologies Used
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib / Seaborn  

## 🚀 How to Run
1. Clone the repository  
2. Install dependencies using `pip install -r requirements.txt`  
3. Run the Jupyter notebook or Python scripts to train the model  
4. Generate `submission.csv` for Kaggle  

## 📌 Author
Udghosh Rao  
