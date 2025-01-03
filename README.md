
# Installation Guide for Student Marks Calculator  

This guide provides detailed steps to set up and run the Student Marks Calculator project locally.

---

## Prerequisites  
Ensure you have the following installed on your system:  
1. **Python**: Version 3.7 or later. Download it from [python.org](https://www.python.org/).  
2. **Pip**: Python package manager (comes pre-installed with Python).  
3. **Git**: To clone the repository. Download from [git-scm.com](https://git-scm.com/).  

---

## Installation Steps  

### 1. Clone the Repository  
Use the following commands to clone the project and navigate to the project folder:  
```bash
git clone https://github.com/dev-harshhh18/college-Project.git
cd College-Project
```  

### 2. Set Up a Virtual Environment (Optional but Recommended)  
A virtual environment helps isolate project dependencies.  
```bash
python -m venv venv  
source venv/bin/activate  # For Linux/Mac  
venv\Scripts\activate     # For Windows  
```  

### 3. Install Required Dependencies  
Install all necessary Python libraries using the `requirements.txt` file:  
```bash
pip install -r requirements.txt
```  

### 4. Run the Application  
Start the application by running the main file:  
```bash
python app.py
```  

---

## Accessing the Application  

1. Open your web browser.  
2. Navigate to: [http://127.0.0.1:5000](http://127.0.0.1:5000).  

---

## Project Structure  

- **`app.py`**: The main Python file that runs the Flask application.  
- **`templates/`**: Contains HTML files for the front-end.  
- **`static/`**: Contains CSS and JavaScript files for styling and interactivity.  
- **`requirements.txt`**: Lists all required Python packages.  

---

## Troubleshooting  

- **Missing Dependencies**: Run `pip install -r requirements.txt` again.  
- **Port Errors**: Ensure no other application is using port 5000.  

---

## Contribution  

We welcome contributions! Follow these steps:  
1. Fork the repository.  
2. Create a new branch (`git checkout -b feature-branch`).  
3. Commit changes and push them (`git push origin feature-branch`).  
4. Submit a pull request.  

---

Enjoy building and enhancing this project!
