[README.md.md](https://github.com/user-attachments/files/22354632/README.md.md)
# Smart Agricultural Master Launcher

This is a Python PyQt5 GUI application for simulating a Smart Agricultural Assistant.  
It integrates multiple smart farming features across four demo applications, including soil analysis, irrigation, artificial lighting, aquaponics, multi-storey farm analytics, biogas, and household gas management.


# Project Basic Structure


INTEGRATED/
├── main.py                  # Master launcher with login and project selection
├── bg_image.jpg              # Background image for GUI
├── project1/                # Basic Smart Farm
│   └── main.py
├── project2/                # Artificial Lighting
│   └── main.py
├── project3/                # Aquaponics + Multi-Storey Analytics
│   └── main.py
├── project4/                # Full Integrated Smart Farm
│   └── main.py
└── README.md                # Project documentation




# Features

1. Login Screen 
   - Username: admin 
   - Password: 1234  
   - Background image with semi-transparent login panel.

2. Master Launcher 
   - Select which project to run.
   - Colorful, rounded buttons with hover effects.
   - Semi-transparent panel with background image.

3. Demo Smart Farm Applications  
    Project 1: Basic Smart Farm  
    Project 2: Artificial Lighting Automation  
    Project 3: Aquaponics + Multi-Storey Analytics  
    Project 4: Full Integrated Smart Farm (includes soil analysis, irrigation, lighting, biogas, household gas, pest detection, alerts)

4. Background Images & Styling  
   -Both login and launcher screens support background images.
   -Semi-transparent panels allow the image to shine through.
   -Responsive GUI with PyQt5.



# Installation & Setup

1. Clone the repository:

2. Install Python if not already installed.

3. Install required packages:

pip install PyQt5

4. Make sure you have your background image inside master_launcher/:

bg_image.jpg

5. Run the master launcher:


python main.py

6. Login with:

Username: admin
Password: 1234


# Notes

- Each project (`project1`, `project2`, etc.) has its own main file.  
- Background images can be changed by replacing `bg_image.jpg`.  
- All projects are demo-ready and allow simulated inputs for sensors, crop selection, and environmental factors.  

---

# Future Enhancements

- Add database authentication for login.  
- Add live sensor integration for soil, water, and lighting data.   
- Include animations and interactive charts for crop analytics.  
- Support multi-user access and farm profiles.
- Voice & Chat Assistant
- Remote alerts via  mobile applications
- Drone & Camera Integration
- Renewable Energy Integration

---

