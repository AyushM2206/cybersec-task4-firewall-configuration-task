# 🔐 Cybersecurity Internship – Task 4: Windows Firewall Configuration

## 🎯 Objective

Configure and test basic firewall rules to allow or block traffic using **Windows Defender Firewall**. Learn how firewalls filter traffic by port and protocol.

---

## 🛠️ Tools Used

- Operating System: Windows 10/11
- Tool: Windows Defender Firewall with Advanced Security (GUI)
- Screenshot Tool: Snipping Tool

---

## ✅ Step-by-Step Implementation

---

### 🧩 Step 1: Open Windows Defender Firewall

- Press `Win + R`, type `wf.msc`, press Enter.
- Firewall configuration window opens.

📸 **Screenshot:**
![1](https://github.com/user-attachments/assets/c9a5755b-0758-4ffd-8b79-9b7324b8829e)


---

### 🧩 Step 2: Create a New Inbound Rule

- Click on **Inbound Rules** in the left pane.
- Click on **New Rule...** in the right pane.
- Choose **Port**, then click **Next**.

📸 **Screenshot:**
![2](https://github.com/user-attachments/assets/15321b9c-33c0-43aa-bb7f-1319d867ece0)

---

### 🧩 Step 3: Specify TCP Port 23 (Telnet)

- Select **TCP**
- Enter **Specific local ports: 23**
- Click **Next**

📸 **Screenshot:**
![3](https://github.com/user-attachments/assets/85a6762c-e14e-4abb-9338-60a778970a43)


---

### 🧩 Step 4: Block the Connection

- Choose **Block the connection**
- Click **Next**

📸 **Screenshot:**
![4](https://github.com/user-attachments/assets/ec0a035e-9c68-41be-88bd-b9983742ec29)


---

### 🧩 Step 5: Apply Rule to All Profiles

- Check all: **Domain**, **Private**, and **Public**
- Click **Next**

📸 **Screenshot:**
![5](https://github.com/user-attachments/assets/13d344ae-6cf5-4662-8086-2fbbfc280afa)


---

### 🧩 Step 6: Name the Rule

- Name it: `Block Telnet Port 23`
- Click **Finish**

📸 **Screenshot:**
![6](https://github.com/user-attachments/assets/bac41fe1-cfa6-43ce-b730-4a47aff07c3a)


---

### 🧩 Step 7: Create Another Rule for Port 22 (SSH)

- Repeat steps for a new inbound rule
- Choose **TCP**, port **22**
- Action: **Allow the connection**

📸 **Screenshot:**
![7](https://github.com/user-attachments/assets/b87b1283-e513-4b7d-9981-7f57abd04c0a)


---

### 🧩 Step 8: Allow the Connection for SSH

- Select **Allow the connection**
- Click **Next**

📸 **Screenshot:**
![8](https://github.com/user-attachments/assets/0a6be05f-0514-4541-b788-b6230405ce32)

---

### 🧩 Step 9: Name the Rule

- Name it: `Allow SSH Port 22`
- Click **Finish**

📸 **Screenshot:**
![9](https://github.com/user-attachments/assets/055a8383-f318-4535-b03d-40b036b5cce2)


---

### 🧩 Step 10: Delete the Telnet Block Rule (Restore State)

- Go to **Inbound Rules**
- Right-click `Block Telnet Port 23` → **Delete**

📸 **Screenshot:**
![10](https://github.com/user-attachments/assets/afc5c887-8497-4e80-933a-28f9b392404b)

---

## 🧠 Key Concepts Learned

- How to configure port-based firewall rules using GUI
- Difference between **allow** and **block** actions
- Security importance of blocking Telnet (port 23) and allowing SSH (port 22)

---

## 👤 Submitted By

**AYUSH MANYANIA**  
Cybersecurity Internship – Task 4  
Windows Firewall Configuration

---


