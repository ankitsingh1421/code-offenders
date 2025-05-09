# 🚀 Space Station Object Detection (Simulated Environment using YOLOv8)

This project is a simulation-based object detection system designed to detect critical objects inside a space station environment. Built during a hackathon, the model is capable of identifying essential equipment under challenging conditions using computer vision and AI.

---

## 🛠️ Built With

<code><img height="30" src="https://raw.githubusercontent.com/github/explore/main/topics/python/python.png"></code>
<code><img height="30" src="https://raw.githubusercontent.com/github/explore/main/topics/ultralytics/ultralytics.png"></code>
<code><img height="30" src="https://raw.githubusercontent.com/github/explore/main/topics/opencv/opencv.png"></code>

---

## 🎯 Objective

The primary goal was to build an AI system capable of detecting three crucial objects in a simulated space station environment using YOLOv8:

- 🧰 Toolbox  
- 🧯 Fire Extinguisher  
- 🫙 Oxygen Tank  

The system should be robust across:
- Varying lighting conditions  
- Occlusions and object overlap  
- Diverse camera angles and distances  

---

## 🧠 AI Engineering Pipeline

### 🔹 Dataset  
- Generated using **FalconEditor** simulating a space station environment.  
- Labeled data for the three objects across multiple frames and lighting scenarios.

### 🔹 Model  
- YOLOv8 trained from scratch and fine-tuned on the custom dataset.  
- Optimized for accuracy and fast inference.

### 🔹 Training Details  
- Framework: **Ultralytics YOLOv8**  
- Trained on high-resolution annotated images  
- Tuned: Batch size, epochs, augmentation, learning rate

---

## 🌟 Features

This AI assistant includes additional features:
- Greet user
- Tell current time and date
- Launch applications/software
- Open any website
- Weather updates for any city
- Location and distance detection
- System status (RAM, CPU, battery)
- Google Calendar events
- Wikipedia person lookup
- Google search
- Play music from YouTube
- Top news headlines
- Send emails
- Math calculation (via WolframAlpha)
- Take notes
- Tell a joke
- IP address info
- Window switcher
- Screenshot functionality
- Hide/unhide folder contents
- Graphical User Interface

---


## Installation
# Clone the repo
git clone <your_repo_url>
cd TestModel

# Create environment (Anaconda)
conda create -n jarvis python=3.8.5
conda activate jarvis

# Install dependencies
pip install -r requirements.txt

# Install PyAudio manually (refer: https://stackoverflow.com/a/55630212)

# Run the app
python main.py

## Code Structure
TestModel/                     # Root folder for the entire project
├── Dockerfile                 # Containerizes all JARVIS functionalities
├── README.md                  # Project overview and instructions
├── render.yaml                # Deployment configuration
├── requirements.txt           # Python dependencies
├── package-lock.json          # Node.js dependencies lock
├── model.pt                   # Trained YOLOv8 model weights
├── find.py                    # Auxiliary backend script
├── main.py                    # Main Python entry point (JARVIS core)
├── run_app.py                 # Application startup wrapper
│
│
├── frontend/                  # Next.js-based user interface
│   ├── app/                   # Next.js “app” directory (app-router)
│   │   ├── layout.tsx         # Global layout (HTML shell)
│   │   ├── page.tsx           # Main entry page
│   │   ├── globals.css        # Global styles
│   │   └── Warning.tsx        # Example UI component
│   │
│   ├── components/            # Reusable React components
│   ├── hooks/                 # Custom React hooks
│   ├── lib/                   # Shared utility functions
│   ├── public/                # Static assets (icons, images)
│   ├── styles/                # Tailwind & custom CSS modules
│   ├── next.config.mjs        # Next.js configuration
│   ├── tailwind.config.ts     # Tailwind CSS configuration
│   └── tsconfig.json          # TypeScript settings
│
└── docker/                    # (optional) Docker-compose configs


- The code structure if pretty simple. The code is completely modularized and is highly customizable
- To add a new feature:
  -  Make a new file in features folder, write the feature's function you want to include
  - Add the function's definition to __init__.py
  - Add the voice commands through which you want to invoke the function



## License
This project is licensed under  2025 Code Offenderd

## Future Improvements
- Generalized conversations can be made possible by incorporating Natural Language Processing
- GUI can be made more nicer to look at and functional
- More functionalities can be added



