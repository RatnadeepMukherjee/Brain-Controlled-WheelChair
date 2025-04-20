🧠 Brain-Controlled Wheelchair
A cutting-edge assistive mobility system that leverages brain-computer interface (BCI) technology to allow individuals with severe motor impairments to control a wheelchair using their brainwaves. This project integrates EEG signal processing, machine learning-based command classification, and motor control to offer a hands-free navigation solution.

🚀 Features
EEG-based Control: Uses real-time brainwave data for directional commands (e.g., forward, stop, left, right).

Signal Processing: Pre-processing of EEG data using filtering, artifact removal, and feature extraction.

ML Command Classification: Trained model (e.g., SVM, CNN, or LSTM) to classify mental commands.

Motor Control Interface: Translates classified commands into wheelchair movement via microcontroller (e.g., Arduino).

Emergency Stop: Safety mechanism to immediately halt the wheelchair in critical situations.

🛠 Tech Stack
Hardware: EEG headset (e.g., NeuroSky MindWave, OpenBCI), Arduino/ESP32, Motor Driver, DC Motors

Software: Python, Arduino C++, Scikit-learn / TensorFlow / PyTorch

Libraries: NumPy, SciPy, MNE, OpenBCI Python, pySerial
