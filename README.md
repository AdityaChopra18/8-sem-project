# Smart Traffic Management System

This project is a final-year endeavor aimed at developing a **Smart Traffic Management System** that utilizes computer vision and machine learning to detect emergency vehicles and traffic incidents, subsequently adjusting traffic signals to optimize flow and ensure safety.

## 🚦 Overview

The system processes real-time video feeds to:
* Detect emergency vehicles (e.g., ambulances, fire trucks)
* Identify traffic incidents such as accidents or congestion
* Dynamically control traffic signals to prioritize emergency vehicles and manage incidents effectively

## 📁 Project Structure

```
smart_traffic_system/
├── main.py
├── emergency_vehicle_detection.py
├── incident_detection.py
├── traffic_signal_controller.py
├── simulator.py
├── utils.py
├── road.mp4
├── road2.mp4
└── road3.mp4
```

## File Descriptions
* **main.py**: The entry point of the application that integrates all modules.
* **emergency_vehicle_detection.py**: Contains logic for detecting emergency vehicles in video feeds.
* **incident_detection.py**: Implements algorithms to identify traffic incidents.
* **traffic_signal_controller.py**: Manages traffic signal states based on detections.
* **simulator.py**: Simulates traffic scenarios for testing purposes.
* **utils.py**: Houses utility functions used across modules.
* **road.mp4**, **road2.mp4**, **road3.mp4**: Sample video files for testing the system.

## 🛠️ Installation and Setup

1. **Clone the repository:**

```bash
git clone https://github.com/AdityaChopra18/8-sem-project.git
cd 8-sem-project
```

2. **Create a virtual environment (optional but recommended):**

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. **Install dependencies:**

```bash
pip install -r requirements.txt
```

*Note: Ensure that `requirements.txt` is present with all necessary dependencies listed.*

## ▶️ Usage

1. **Run the main application:**

```bash
python main.py
```

2. **Testing with sample videos:**
   The application uses the provided `road.mp4`, `road2.mp4`, and `road3.mp4` files to simulate real-world scenarios.

## 📚 Features

* **Emergency Vehicle Detection**: Utilizes computer vision techniques to identify emergency vehicles in traffic.
* **Incident Detection**: Detects anomalies such as accidents or traffic jams.
* **Adaptive Traffic Signal Control**: Adjusts signal timings to prioritize emergency vehicles and manage incidents.
* **Simulation Environment**: Provides a controlled environment to test and validate system performance.

## 🤝 Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.

## 📄 License

This project is licensed under the MIT License.

## 📧 Contact

For any inquiries or feedback, please contact Aditya Chopra.