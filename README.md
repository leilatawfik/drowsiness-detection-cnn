# Drowsiness Detection Using CNNs (Eye State & Yawn Analysis)

This project explores a computer vision approach to detecting drowsiness using convolutional neural networks (CNNs). Separate image-based models were trained on eye-state and yawn datasets to identify fatigue-related facial cues relevant to driver and heavy-machinery operator safety.

## Project Overview
Drowsiness and fatigue significantly impair reaction time and decision-making in safety-critical environments. This project investigates whether lightweight CNN models trained on facial cues can reliably distinguish alert and drowsy states using only image data.

## Methodology
Two independent CNN models were developed:
- **Eye-state model** to classify open vs. closed eyes
- **Yawn model** to detect yawning behavior from facial images

Models were trained and evaluated using standard classification metrics, with an emphasis on recall and false-negative rate due to the safety implications of missed detections.

## Results
The trained models achieved strong performance across evaluation metrics, demonstrating the feasibility of vision-based fatigue monitoring systems. Results from the eye and mouth model can separately be found in the assets folder. 


## Data
Image datasets are not included in this repository due to size and licensing constraints.  
Publicly available eye-state and yawn image datasets were used and loaded locally during training.  
Instructions for dataset structure and loading are documented in the notebook.

## Tech Stack
- Python
- TensorFlow / Keras
- NumPy, Pandas, Matplotlib
- Scikit-learn

## Attribution
This repository is a portfolio-focused summary of a course group project.  
Original group repository: **https://github.com/leilatawfik/ENGG680_ML_Project.git**  

My contributions included model design, training, evaluation, and analysis.
