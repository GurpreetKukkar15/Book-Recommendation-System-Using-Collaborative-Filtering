# Book-Recommendation-System-Using-Collaborative-Filtering
A full-stack book recommendation system using collaborative filtering and machine learning, built with Python, Flask, and MySQL.




##  Overview

This project is a **Book Recommendation System** that suggests personalized books to users using **collaborative filtering** techniques. It leverages **implicit user feedback** and similarity-based machine learning models to deliver relevant recommendations through a **Flask-based web application**.

The system also addresses common recommendation challenges such as the **cold-start problem** by recommending trending books to new users.

---

##  Features

* Personalized book recommendations using **Collaborative Filtering**
* Handles **cold-start users** with popularity-based suggestions
* Full-stack web application with user authentication
* Efficient ML inference using pre-trained models
* Admin and user dashboards
* Scalable and modular architecture

---

## Tech Stack

### Backend & ML

* Python
* Flask
* Pandas, NumPy
* Scikit-learn
* Pickle (model serialization)

### Frontend

* HTML
* CSS
* Jinja Templates

### Database

* MySQL

---

##  How It Works

1. **Data Processing**

   * User–book interaction data is transformed into a user-item matrix.
   * Implicit feedback is used to understand user preferences.

2. **Recommendation Engine**

   * Collaborative filtering using **cosine similarity**.
   * Similar users/books are identified to generate recommendations.

3. **Cold-Start Handling**

   * New users receive recommendations based on **popular and trending books**.

4. **Web Integration**

   * ML models are serialized using Pickle.
   * Flask serves recommendations in real time via RESTful routes.

---

## 📂 Project Structure

```
Book-Recommendation-System/
│
├── app.py                  # Main Flask application
├── model/                  # Trained ML models (.pkl)
├── templates/              # HTML templates
├── static/                 # CSS and assets
├── dataset/                # Book and user datasets
├── requirements.txt        # Python dependencies
└── README.md               # Project documentation
```

---

## ▶️ How to Run Locally

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/book-recommendation-system.git
cd book-recommendation-system
```

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Configure Database

* Create a MySQL database
* Update database credentials in the configuration file

### 4️⃣ Run the Application

```bash
python app.py
```

### 5️⃣ Open in Browser

```
http://127.0.0.1:5000/
```

---

## Future Enhancements

* Add **content-based filtering** using book genres and descriptions
* Implement **matrix factorization (SVD)**
* User clustering based on demographics
* Deploy on **AWS / Docker**
* Improve scalability for large datasets

---

## Learning Outcomes

* Hands-on experience with **recommendation systems**
* Integration of **machine learning models into web applications**
* Understanding of real-world challenges like data sparsity and cold start
* End-to-end project development (ML + Backend + DB + UI)

---

## ⭐ If you like this project

Give it a star ⭐ and feel free to fork or contribute!

