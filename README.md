
# 💰 **Expense Tracker with Analytics Dashboard** 📊  

A user-friendly web application built with Flask to help you manage your expenses and track your financial health with ease.  

---

## **✨ Features**  
- 🔐 **User Authentication**: Secure login and registration system.  
- 📝 **Expense Management**: Add, view, and manage expenses effortlessly.  
- 📈 **Dashboard Analytics**: Visualize your expenses by category and date.  
- 🌐 **Responsive Design**: Clean and intuitive interface for all devices.  

---

## **📂 Project Structure**  

```plaintext
expense-tracker/
│
├── app/
│   ├── __init__.py        # Flask app factory
│   ├── models.py          # Database models
│   ├── routes.py          # Application routes
│
├── templates/
│   ├── base.html          # Base template with layout
│   ├── dashboard.html     # Dashboard page
│   ├── login.html         # Login form
│   ├── register.html      # Registration form
│
├── static/
│   ├── style.css          # CSS styles
│
├── app.py                 # Main application entry point
├── requirements.txt       # Project dependencies
└── config.py              # Application configuration
```

---

## **🛠️ Technologies Used**

### **Backend**  
- 🌟 Flask: Lightweight Python web framework.  
- 🗂️ SQLite: File-based relational database.  

### **Frontend**  
- 🎨 HTML5 and CSS3: Clean and modern user interface.  
- 🌐 Jinja2: Powerful templating engine.  

---

## **🚀 Setup Instructions**

1. **📥 Clone the Repository**  
   ```bash
   git clone https://github.com/your-username/expense-tracker.git
   cd expense-tracker
   ```

2. **🧪 Create a Virtual Environment**  
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **📦 Install Dependencies**  
   ```bash
   pip install -r requirements.txt
   ```

4. **▶️ Run the Application**  
   ```bash
   python app.py
   ```

5. **🌐 Access the Application**  
   Open your browser and navigate to `http://127.0.0.1:5000`.  

---



## **💡 Future Enhancements**  
- 📊 Add interactive graphs and charts for analytics (e.g., monthly expenses).  
- 🔄 Integrate APIs for importing/exporting data.  
- 🛠️ Allow customization of expense categories.  
- ☁️ Deploy the application on cloud platforms like Heroku or AWS.  

---

## **📜 License**  
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.  

