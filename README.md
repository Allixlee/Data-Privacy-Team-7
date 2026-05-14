# Data-Privacy-Team-7

Social media platforms such as TikTok collect large amounts of biometric and facial data used for various purposes, such as personalized content and ad recommendations, analytics, and demographic classifications. Information can be collected not only from posted content, but from imported or drafted content, regardless of whether they are saved or published. The information taken from facial analysis on these platforms may be beyond what users intend to share. We aim to investigate what characteristics and information can be inferred from facial analysis data collected from users and how it influences content recommendation and other features on the platform.

The notebook in this repository uses the Facer and DeepFace frameworks to detect and analyze the faces of our AI generated personas to gather the facial attributes and traits associated to the personas.

Facer: https://github.com/FacePerceiver/facer
DeepFace: https://github.com/serengil/deepface


## Setup Instructions:
1. Download the ipynb notebook and Personas folder
2. Import the notebook and Personas folder to Google Drive
3. Open the notebook in Google Colab
4. Click on the arrow pointing down on the top right corner next to RAM/Disk
5. Click "Change runtime" type and change "Hardware accelerator" to "T4 GPU" and click save
6. Ensure "folder_path" in cell 2 points to the location of the Personas folder
7. Press "Run all"