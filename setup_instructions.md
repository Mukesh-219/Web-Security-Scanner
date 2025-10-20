# ⚙️ Setup Instructions – Web Security Scanner

## Prerequisites
- Windows/Linux system  
- XAMPP installed (Apache + MySQL)  
- OWASP ZAP installed  
- DVWA (Damn Vulnerable Web Application)

---

## Step 1 – Install & Configure DVWA
1. Download DVWA from GitHub: https://github.com/digininja/DVWA  
2. Extract the folder into your XAMPP `htdocs/` directory (e.g., `C:/xampp/htdocs/`)  
3. Go to `http://localhost/dvwa/setup.php` and click *Create / Reset Database*  
4. Login with (default DVWA credentials):
   - Username: `admin`
   - Password: `password`

---

## Step 2 – Setup OWASP ZAP
1. Launch OWASP ZAP → click **Manual Explore**  
2. Enter `http://localhost/dvwa` as the target  
3. Start **Active Scan**  
4. After scan completes, export report → place it in `/results/`

---

## Step 3 – Analyze the Report
Open `/results/sample-scan-report.txt` to view example findings (SQLi/XSS/missing headers).

---

## 💡 Pro Tip
Always perform security scans only on systems you own or have explicit permission to test. Never scan live/third-party websites without authorization.
