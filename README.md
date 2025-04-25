# 🚀 Impact DevOps  
**"Revolutionizing Restaurant Management with Real-Time Predictions and Smart Stocking"**  

---

## 📌 Problem Statement  
**Problem Statement – Reduce ingredients and vegetables wastage in restaurants**  

---

## 🎯 Objective  
Our solution targets restaurant operations in 3-star and 4-star hotels. We aim to solve real-time stock prediction, cost optimization, and smart purchase planning by leveraging data-driven decision-making. By integrating real-time price predictions, market trends, and stock tracking, we help restaurants reduce wastage, increase profitability, and improve efficiency.  

---

## 🧠 Team & Approach  
**Team Name:**  
Impact DevOps  

**Team Members:**  
- 👨‍💻 Karunagaran Velmourougane  
- 👩‍💻 Leena  
- 👩‍💻 Sandhiya  
- 👨‍💻 Monesh  

**Our Approach:**  
We selected this problem because it aligns perfectly with the daily struggles of restaurant managers—balancing stock, sales, and purchasing efficiently. We tackled real-time prediction delivery, cross-tech integration (PHP, Python, JS), and reliable Fluvio streaming under one umbrella. Major pivots came from switching traditional REST to WebSockets for real-time UI, and integrating Prophet + Fluvio for high-accuracy forecasting.  

---

## 🛠️ Tech Stack  
**Core Technologies Used:**  
- **Frontend:** JavaScript, React.js, WebSockets  
- **Backend:** PHP (CodeIgniter), Python (Flask + Prophet), Fluvio  
- **Database:** MySQL  
- **APIs:** Flask API for prediction, Fluvio for real-time streaming  
- **Hosting:** XAMPP (for PHP + MySQL), Localhost (Python + Flask)  

**Sponsor Technologies Used:**  
- ✅ **Fluvio:** For real-time grain price prediction streaming  

---

## ✨ Key Features  
- ✅ Real-time grain price predictions using Prophet  
- ✅ WebSocket-powered live UI updates for stock and pricing  
- ✅ Hybrid architecture using PHP, Python, and React  
- ✅ Smart purchase suggestions based on predicted market trends  

---

## 📽️ Demo & Deliverables  
- **📑 Pitch Deck:** [Impact DevOps Presentation](https://gamma.app/docs/Impact-DevOps--3zuz4vua0zj47t8?mode=present)  
- **📺 How We Use Fluvio:** [Watch on YouTube](https://www.youtube.com/watch?v=kaXSQc5pchg)  

---

## ✅ Tasks & Bonus Checklist  
- ✅ All members followed social channels & filled the form  
- ✅ Bonus Task 1 - Shared badges (2 points)  
- ✅ Bonus Task 2 - Signed up for Sprint.dev (3 points)  

---

## 🧪 How to Run the Project  

### **Requirements**  
- 🖥️ Ubuntu/Linux (mandatory)  
- 🐍 Python 3  
- 🟢 Node.js  
- 🛠️ XAMPP (for PHP + MySQL)  
- 🌐 Fluvio CLI  
- 🧰 Git  

---

### **Local Setup Instructions**  

1️⃣ **Clone the Repository**  
```bash
git clone https://github.com/Info-God/SmartChef_Hackhazards25
```  

2️⃣ **Frontend Setup (React)**  
```bash
npm install
npm install socket.io-client
npm run dev
```  

3️⃣ **PHP + MySQL Setup**  
- Open XAMPP  
- Start Apache and MySQL  
- Import `hack.sql` into phpMyAdmin  

---

## 🐍 Flask and Fluvio Integration Guide  

### 📑 Table of Contents  
1. [⚙️ Prerequisites](#prerequisites)  
2. [🖥️ System Setup](#system-setup)  
3. [📦 Python Environment](#python-environment)  
4. [🚀 Fluvio Installation](#fluvio-installation)  
5. [🌐 Flask Application Setup](#flask-application-setup)  
6. [▶️ Running the System](#running-the-system)  
7. [🛠️ Troubleshooting](#troubleshooting)  
8. [📚 References](#references)  

---

### ⚙️ Prerequisites  
- 🖥️ **Ubuntu/Linux environment**  
- 🔑 Terminal access with `sudo` privileges  
- 🐍 Python 3 installed  
- 🌐 Stable internet connection  

---

### 🖥️ System Setup  

#### 🔄 Update Your System  
```bash
sudo apt update && sudo apt upgrade -y
```  

#### 📦 Install Core Dependencies  
```bash
sudo apt install -y python3 python3-pip python3-venv git curl build-essential
```  

---

### 📦 Python Environment  

#### 🛠️ Create Virtual Environment  
```bash
python3 -m venv venv
source venv/bin/activate
```  

#### 📜 Install Required Packages  
```bash
pip install flask flask-socketio flask-cors pandas mysql-connector-python prophet
```  

---

### 🚀 Fluvio Installation  

#### 🛠️ Install Fluvio CLI  
```bash
curl -fsS https://hub.infinyon.cloud/install/install.sh | bash
```  

#### 🔗 Add Fluvio CLI to PATH  
```bash
echo "export PATH=\"${HOME}/.fvm/bin:${HOME}/.fluvio/bin:\${PATH}\"" >> ~/.zshrc
source ~/.zshrc
```  

#### 🦀 Setup Rust (Required by Fluvio)  
```bash
curl --proto '=https' --tlsv1.2 https://sh.rustup.rs -sSf | sh
```  

#### 🛠️ Install SDF CLI  
```bash
fvm install sdf-beta9
```  

#### 🐍 Install Python Binding  
```bash
pip install fluvio
```  

#### ⚙️ Fluvio Setup & Topic Creation  
- **Delete Existing Cluster (if any):**  
```bash
fluvio cluster delete
```  
📝 *Type `local` when asked to confirm.*  

- **Start Fluvio Cluster:**  
```bash
fluvio cluster start
```  

- **Create Topic:**  
```bash
fluvio topic create grain-predictions
```  

---

### 🌐 Flask Application Setup  

#### 📂 Project Structure  
```
PythoEngine/
├── venv/
├── MachineLearningModel.py
```  

---

### ▶️ Running the System  

#### 🚀 Start Fluvio:  
```bash
fluvio cluster start
```  

#### ▶️ Run Flask App:  
```bash
python app.py
```  

---

## 🛠️ Troubleshooting  

| ⚠️ **Issue**              | 🛠️ **Solution**                              |  
|---------------------------|-----------------------------------------------|  
| Fluvio cluster fails      | Run `fluvio cluster delete` then restart      |  
| Python import errors      | Reinstall requirements in virtual environment |  

---

## 📚 References  
- 📖 [Fluvio Documentation](https://fluvio.io/docs/)  
- 📖 [Flask Documentation](https://flask.palletsprojects.com/)  
- 📖 [Python Virtual Environments](https://docs.python.org/3/library/venv.html)  

---

*Prepared with ❤️ by the **Impact DevOps** Team*
