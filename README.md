# 🎥 Launch Windows Virtual Machine on AWS & Connect via RDP

## 📌 Project Description

This project demonstrates how to launch a Windows Virtual Machine (VM) on Amazon Web Services (AWS) using EC2 and access it from a local Windows machine using Remote Desktop Protocol (RDP).

The video tutorial provides a step-by-step explanation of setting up the cloud environment and connecting to it securely.

---

## 🎯 Objective

* Launch a Windows EC2 instance on AWS
* Configure security settings (RDP access)
* Retrieve administrator credentials
* Connect to the VM from a local machine
* Understand real-world use of cloud-based systems

---

## 📽️ Video Demonstration

👉 [Watch the Video](https://youtu.be/1H27iYHEFYA?si=6tqt91bNZOK3NPxO)

---

## ☁️ Technologies Used

* Amazon Web Services (AWS EC2)
* Windows Server (AMI)
* Remote Desktop Protocol (RDP)
* OBS Studio (for recording)

---

## 🛠️ Steps Performed

### 1️⃣ Login to AWS Console

* Open AWS Management Console
* Login with your credentials

### 2️⃣ Launch EC2 Instance

* Navigate to EC2 Dashboard
* Click **Launch Instance**
* Configure:

  * Name: `Windows-VM`
  * AMI: Microsoft Windows Server
  * Instance Type: `t2.micro` (Free Tier)
  * Key Pair: Create and download `.pem` file

💡 *Important:* Keep the key file safe—it is required to decrypt the password.

---

### 3️⃣ Configure Security Group

* Allow **RDP (Port 3389)**
* Restrict access to your IP for better security

---

### 4️⃣ Launch Instance

* Click **Launch Instance**
* Wait until instance status is **Running**

---

### 5️⃣ Get Windows Password

* Select instance → Click **Connect**
* Go to **RDP Client tab**
* Upload `.pem` file
* Decrypt password

---

### 6️⃣ Connect Using Remote Desktop

* Open Remote Desktop Connection (`mstsc`)
* Enter:

  * Public IP address
  * Username: `Administrator`
  * Password: (decrypted password)

🎉 You are now connected to your AWS Windows Virtual Machine!

---

## 💡 Real-World Use Cases

* Remote work environments
* Cloud-based development
* Software testing environments
* Running applications remotely

---

## 🎬 Video Production Details

* Screen Recording: OBS Studio
* Facecam: Laptop / External Camera
* Editing: Basic cuts and zoom effects

---

## 👨‍💻 Author

* **Your Name**
* Course / Department

---

## 📄 Note

This project is created for academic purposes only.
