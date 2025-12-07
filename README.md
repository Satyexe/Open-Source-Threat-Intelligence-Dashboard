# 🛡️ Open-Source Threat Intelligence Dashboard

A powerful and intelligent **Cyber Threat Intelligence (CTI) Dashboard** built to collect, analyze, and visualize real-time cybersecurity threat information from public sources including government advisories, IP threat lookups, global maps, and open-source data.  
This project is designed for **Security Analysts, SOC teams, Cybersecurity Researchers, and Students** who want a centralized tool to monitor emerging cyber threats with actionable intelligence.

---

## 🚀 Live Demo (Deployment Link)

🔗 **Hosted Link:**   

---

## 📸 Screenshots

> **Screenshots will be added here**

| Dashboard Home | Threat Advisory Table |
|----------------|-----------------------|
| ![Home Screenshot]<img width="1108" height="497" alt="image" src="https://github.com/user-attachments/assets/321df63c-bc79-4c3e-b45e-70b526deda50" />
 | ![Advisory Screenshot]<img width="1289" height="456" alt="image" src="https://github.com/user-attachments/assets/c8b8651b-a774-4fbb-b69a-ca0f23974ff5" />
 |

| IP Lookup and Map View |
|------------------------|
| ![Map Screenshot]<img width="640" height="922" alt="image" src="https://github.com/user-attachments/assets/081ed5c3-bbd6-466c-8fed-69583e5ee432" />
 |

---

## 📌 Key Features

### 🔍 Threat Intelligence Aggregation
- Real-time **US-CERT / CISA cybersecurity advisories**
- Threat lookup and vulnerability tracking
- Data structured in readable UI tables and cards

### 🌍 Geolocation & IP Lookup
- Track threat origin and IP information
- Maps and structured location insights
- Organization & ISP details

### 📊 Dashboard UI & Analytics
- Clean, responsive, professional cybersecurity dashboard interface
- Centralized threat visualization

### 🛠 Technical Architecture
- Modular codebase with scraper engines
- Multi-source data gathering
- Designed for real-world SOC usage

---

## 🧠 Project Goals

- Create an open-source threat intelligence platform accessible for analysis & education
- Provide automation for advisory collection and analysis
- Help SOC teams accelerate threat visibility and response time
- Support students with hands-on cybersecurity project experience

---

## 🧑‍💻 Tech Stack

| Category | Technologies |
|----------|--------------|
| Backend | Python, Flask |
| Frontend | HTML, CSS, JavaScript, Bootstrap |
| Scraping | BeautifulSoup, Requests |
| Deployment | Render |
| Data Sources | CISA / US-CERT, ipwhois.app, external feeds |

---

## 📂 Project Structure

```bash
Open-Source-Threat-Intelligenece-Dashboard/
│── app.py                    # Main Flask application
│── requirements.txt          # Python dependencies
│── scraper/
│   ├── uscert_fetcher.py     # Scraper for advisories
│── templates/
│   ├── index.html            # Frontend UI template
│── static/
│   ├── css/ js/ images       # Static assets
│── README.md
