# 🛡️ SafeVisionAI

**SafeVisionAI** is an advanced real-time visual monitoring and threat detection system designed to enhance safety for women.  
It leverages computer vision and machine learning to analyze live CCTV footage, detect potentially unsafe situations, and immediately alert authorized personnel such as security staff or law enforcement.

The system also maintains a structured database of incidents for monitoring, analysis, and reporting.

---

## 🚀 Features

- **Real-Time Threat Detection**  
  Monitors live CCTV video feeds and identifies unsafe situations using a trained machine learning model.

- **Automated Alerts**  
  Sends instant notifications to admins, security personnel, or police when a threat is detected.

- **Incident Logging**  
  Records detected events in a structured database for future review and analysis.

- **User-Friendly Interface**  
  Provides an intuitive dashboard for real-time monitoring and incident management.

- **Scalable Architecture**  
  Supports integration with multiple CCTV cameras for large-area surveillance.

---

## 🧰 Technologies Used

### Frontend
- HTML  
- CSS  
- JavaScript  

### Backend
- Flask  
- Python  

### Computer Vision & ML
- OpenCV  
- TensorFlow / PyTorch  
- CNN-based custom threat detection model  

### Database
- MySQL  

---

## ⚙️ How It Works

1. Live video feeds are captured from connected CCTV cameras.  
2. Video frames are processed in real time using OpenCV.  
3. A CNN-based model analyzes frames to detect suspicious or unsafe activities.  
4. When a threat is identified:
   - Alerts are sent to authorized personnel.
   - The incident is logged in the database.
5. Admins and security teams can review incidents through the dashboard.

---

## 📸 Screenshots

![Dashboard View](https://github.com/user-attachments/assets/6577802d-4146-4965-94f1-1c37c7df499b)
![Incident Monitoring](https://github.com/user-attachments/assets/ad9c1179-cd16-4d89-b33d-c6cc998e988a)
![Threat Detection View](https://github.com/user-attachments/assets/e2e48958-abd7-48f4-bd1d-7248f36cc6ad)
![Alert System](https://github.com/user-attachments/assets/bf6ebb21-6b49-416e-a80b-da7756bed814)
![System Overview](https://github.com/user-attachments/assets/0558ed72-cb13-4223-9847-17bff47317f5)

---

## 🛠️ Installation

```bash
# Clone the repository
git clone https://github.com/SHRIKANTAMBATKAR/SafeVision-AI.git

# Navigate to the project directory
cd SafeVision-AI

# Install dependencies
pip install -r requirements.txt

# Run the application
python app.py
```
### Future Scope

- Integration with mobile applications for instant alerts

- Improved ML models with multi-class threat detection

- Expansion into public safety systems and smart city surveillance

📌 Note

This project is developed for educational, research, and social-impact purposes and demonstrates the application of computer vision and AI in real-world safety systems.

👨‍💻 Author

Shrikant Ambatkar
B.Tech Computer Science


