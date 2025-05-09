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

## Features

It can do a lot of cool things, some of them being:

- Greet user
- Tell current time and date
- Launch applications/softwares 
- Open any website
- Tells about weather of any city
- Open location of any place plus tells the distance between your place and queried place
- Tells your current system status (RAM Usage, battery health, CPU usage)
- Tells about your upcoming events (Google Calendar)
- Tells about any person (via Wikipedia)
- Can search anything on Google 
- Can play any song on YouTube
- Tells top headlines (via Times of India)
- Plays music
- Send email (with subject and content)
- Calculate any mathematical expression (example: Jarvis, calculate x + 135 - 234 = 345)
- Answer any generic question (via Wolframalpha)
- Take important note in notepad
- Tells a random joke
- Tells your IP address
- Can switch the window
- Can take screenshot and save it with custom filename
- Can hide all files in a folder and also make them visible again
- Has a cool Graphical User Interface

## API Keys
To run this program you will require a bunch of API keys. Register your API key by clicking the following links

- [OpenWeatherMap API](https://openweathermap.org/api)
- [Wolframalpha](https://www.wolframalpha.com/)
- [Google Calendar API](https://developers.google.com/calendar/auth)
  
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


TestModel                     # Main folder for all features
├── Dockerfile                # All functionalities of JARVIS
├── README.md                 # Project overview
├── __pycache__              # Python bytecode cache
├── find.py                  # Additional backend script
├── main.py                  # Main Python entry point
├── model.pt                 # Trained ML model file
├── package-lock.json        # Backend package lock file
├── render.yaml              # Deployment configuration
├── requirements.txt         # Python dependencies
├── run_app.py               # App startup script
├── frontend                 # Frontend (Next.js) application
│   ├── app                  # Main Next.js app directory
│   │   ├── Warning.tsx
│   │   ├── globals.css
│   │   ├── layout.tsx
│   │   └── page.tsx
│   ├── components           # UI components
│   ├── components.json      # Components config
│   ├── hooks                # Custom React hooks
│   ├── lib                  # Utility libraries
│   ├── next-env.d.ts
│   ├── next.config.mjs      # Next.js configuration
│   ├── node_modules
│   ├── package.json         # Frontend dependencies
│   ├── package-lock.json
│   ├── pnpm-lock.yaml
│   ├── postcss.config.mjs
│   ├── public               # Static assets
│   ├── styles               # Tailwind and custom styles
│   └── tailwind.config.ts   # Tailwind CSS configuration


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



