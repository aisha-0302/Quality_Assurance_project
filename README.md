# 🧪 Quality_Assurance_Project  
## Automated Login Testing with Selenium  

### 📌 Project Overview  
This project automates **login functionality testing** for a web application using **Selenium**, **Python**, and **Pytest**.  
It validates both **valid and invalid login attempts**, captures screenshots of failures, and generates detailed **test reports** and **defect logs**.

**Key Outputs:**  
- ✅ **HTML Test Report:** `report.html`  
- ⚠️ **Defect Log:** `defects_log.csv`  
- 📸 **Screenshots Folder:** `/screenshots`  

---

### ⚙️ Prerequisites  

#### 🔧 Software Requirements  
- **Python 3.8+**  
- **Google Chrome Browser**  
- **ChromeDriver** *(auto-installed via `webdriver_manager`)*  

#### 📦 Python Libraries  
Install all required dependencies using:
```bash
pip install -r requirements.txt


Step 1: Create & Activate Virtual Environment
cd selenium_tests
python -m venv venv


Activate the environment:
Windows: venv\Scripts\activate
macOS/Linux: source venv/bin/activate

Step 2: Install Dependencies
pip install selenium pytest pytest-html webdriver-manager

Execute Tests
Run all tests and generate the HTML report:
pytest conftest.py --html=report.html --self-contained-html

This command:
Runs all test cases
Generates a detailed HTML report
Saves it as report.html in the project directory
Captures screenshots automatically when any test fails

Step 4: View Results
After execution:
📄 Report: Open report.html in any browser
⚠️ Defects: Check defects_log.csv
📸 Screenshots: Found in /screenshots folder

🧑‍💻 Author
S.Aisha Siddika
B.Tech. Computer Science Engineering
Vel Tech, Chennai

📘 Project: Automated Web Login Testing using Selenium and Pytest
