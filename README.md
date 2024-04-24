# Healthcare Recommendation System: Diabetic Retinopathy Detection

## Overview:
This repository contains the codebase for a healthcare recommendation system focused on diabetic retinopathy detection and doctor recommendation. The system utilizes artificial intelligence techniques to analyze medical data and provide personalized recommendations for patients.

## Features:
- Diabetic Retinopathy Detection: Our system includes a quantum-based CNN model trained to detect diabetic retinopathy from retinal images.
- Information Page: Provides detailed information about diabetic retinopathy, its symptoms, causes, and treatment options.
- Analytics Page: Allows users to track their medical records, including test results, treatment history, and appointments.
- Grade Checking Page: Enables users to upload retinal images to assess the severity of diabetic retinopathy using the trained model.
- FAQ Page: Offers answers to frequently asked questions about diabetic retinopathy to educate users.

## Future Prospects:
- Disease Detection Expansion: Extend the system to detect various other diseases using medical images, such as jaundice detection from liver images, leveraging advanced AI techniques.
- Enhanced Doctor Recommendation: Implement AI algorithms to match patients with doctors based on their specialty, expertise, and availability, facilitating seamless appointment scheduling.
- Doctor Dashboard: Develop a dashboard for doctors to manage their schedules, view patient conditions, prescribe medications, and book appointments efficiently.

## Project Source code structure

The following explains the project structure:
- The `src` folder contains all the source code related to the platform.
- The `src/main.ipynb` contains the QNN model evaluation on the IDRID dataset.
- The `src/ui` folder contains the React-based UI of the platform.

## Project Specifications

Head over to the `src/dataset_evaluation.py` file to get started.
- The QNN model is validated on the **IDRID** dataset.
- The implemented QNN model achieves an accuracy of **57.1429 %** on the **IDRID** dataset.
- You can access the dataset on this [link](https://ieee-dataport.org/open-access/indian-diabetic-retinopathy-image-dataset-idrid)

> **NOTE:** The Project only works in Ubuntu/MacOS having Python version : **3.9.x**


## Setup and Usage:
Dependencies:
- Python 3.x
- TensorFlow
- Quantum Computing Libraries 

Running the System:
- Execute the backend server using the provided scripts or commands.
- Start the frontend server to launch the user interface.
- Follow the instructions provided in the respective directories for further details on running individual components.
