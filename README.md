# 🔐 Web Security Scanner

A simple vulnerability-analysis setup using **OWASP ZAP** and **DVWA** to explore common web-app security issues like **SQL Injection**, **XSS**, and **CSRF**.

---

## 🧰 Tech Stack
- OWASP ZAP  
- XAMPP + DVWA  
- HTTP Protocols & Headers  

---

## ⚙️ Features
- Automated scanning & manual inspection  
- HTTP request/response analysis  
- Beginner-friendly setup for DVWA and ZAP  

---

## 🚀 Setup & Run
1. Install **XAMPP** and start Apache & MySQL services.  
2. Download and place **DVWA** inside `htdocs/` folder of XAMPP.  
3. Run `http://localhost/dvwa/setup.php` to initialize the test database.  
4. Open **OWASP ZAP**, target `http://localhost/dvwa`, and begin scanning.  
5. Export reports and place them in the `results/` folder in this repo.

---

## 📊 Example Output
- SQL Injection vulnerabilities detected  
- Missing security headers  
- Reflected XSS alerts  

Reports are stored inside `/results/sample-scan-report.txt`.

---

## 📸 Screenshots
(Replace placeholder images in `screenshots/` with your real captures when available.)

---

## 📚 Learning Outcome
- Understanding **client-server communication security**  
- Basics of **ethical web testing**  
- Hands-on with real-world security scanners  

---

## 👩‍💻 Author
**Jigisha Diksha**  
[LinkedIn](https://linkedin.com/in/jigisha-diksha-51a39b2) • [GitHub](https://github.com/Jigisha-Diksha)
