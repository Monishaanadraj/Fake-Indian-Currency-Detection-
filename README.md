# 💵 Fake Indian Currency Detection Web App  

## 📌 Overview  
The **Fake Indian Currency Detection Web App** helps users identify counterfeit Indian currency notes by analyzing uploaded images. Using **machine learning (ML) models** and **image processing techniques**, the app provides an instant authenticity check for banknotes.  

## 🚀 Features  
✔️ **Upload Currency Note Image** (JPEG, PNG, etc.)  
✔️ **Image Preprocessing** (Enhancement, Noise Removal)  
✔️ **Fake vs. Real Currency Detection** (Using ML/Deep Learning)  
✔️ **Instant Results with Confidence Score**  
✔️ **User Authentication** 

## 🛠️ Tech Stack  
- **Frontend:** React.js / HTML, CSS, JavaScript  
- **Backend:** Node.js, Express.js / Django, Flask  
- **Database:** MySQL / MongoDB (For logs & user data)  
- **ML Model:** TensorFlow / OpenCV / Scikit-learn  
- **UI Framework:** Tailwind CSS / Bootstrap  

## 🔧 Installation  

### **1. Clone the Repository**  
```sh
git clone https://github.com/your-username/fake-currency-detection.git
cd fake-currency-detection
```

### **2. Install Dependencies**  
#### **For Backend**  
```sh
pip install -r requirements.txt  # If using Python (Flask/Django)
npm install  # If using Node.js
```
#### **For Frontend**  
```sh
cd frontend
npm install
```

### **3. Set up Environment Variables**  
Create a `.env` file in the root directory and add:  
```sh
DB_HOST=your-database-host
DB_USER=your-database-user
DB_PASSWORD=your-database-password
MODEL_PATH=path/to/your/ml_model.h5
```

### **4. Run the Application**  
#### **Start Backend**  
```sh
python app.py  # Flask  
npm start  # Node.js  
```
#### **Start Frontend**  
```sh
cd frontend
npm start
```

## 🎯 How It Works  
1. **User uploads an image of an Indian currency note.**  
2. **The system processes the image (cropping, resizing, enhancing).**  
3. **ML model analyzes security features like watermarks, serial numbers, colors, etc.**  
4. **The app returns a "Real" or "Fake" result with a confidence score.**  

**Homepage:
A website homepage for identifying fake Indian currency using Convolutional Neural Networks (CNN).
Navigation bar includes Home and Login options.**

![Picture14](https://github.com/user-attachments/assets/ba9f739a-15d8-4892-ae4d-6e55b75a105e)


**Login Page:
Provides fields for Username and Password.
Includes a Signup link for new users.**

![Picture15](https://github.com/user-attachments/assets/07c87196-7d49-4917-916f-403e4e64d27e)


**Signup Page:
Allows users to enter Username, Email ID, and Password for account creation.
Includes a Login link for existing users.**

![Picture16](https://github.com/user-attachments/assets/594498ba-4f04-4691-b8c4-3967652dd885)


**Fake Currency Detection Result Page:
Displays an uploaded Indian currency note for verification.
Uses CNN to predict whether the currency is Real or Fake.**

![Picture17](https://github.com/user-attachments/assets/5dbd5cbf-2add-427c-ab3d-c5378add8ec0)

![Picture18](https://github.com/user-attachments/assets/613b710f-02d0-4170-acee-919789283a6b)

![Picture19](https://github.com/user-attachments/assets/ab338bc4-68b7-4697-8f9a-fe1cfb9c84d3)

**This page shows performance analysis of the Accuracy , precision , recall and F-measure.**
![Picture20](https://github.com/user-attachments/assets/f6ff3ea1-1bda-4000-b3ba-b7f6bed5ebdc)

![Picture21](https://github.com/user-attachments/assets/519cdfd4-4060-434e-80d9-cff7e7197c4c)














