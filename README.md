OCT Cyst Detection
This repository contains a Jupyter Notebook (.ipynb) for analyzing Optical Coherence Tomography (OCT) images to detect and identify cysts. The project leverages image processing and analysis techniques to assist in automated ophthalmic diagnostics.
Overview
OCT imaging is widely used in ophthalmology to visualize retinal structures and identify abnormalities such as cysts, which can indicate conditions like diabetic macular edema or age-related macular degeneration. This notebook provides a workflow for preprocessing OCT images, detecting cyst regions, and visualizing the results.
Features
Image Loading & Preprocessing: Supports reading OCT image datasets and preparing them for analysis.
Cyst Detection: Implements techniques for identifying cystic regions within OCT scans.
Visualization: Generates visual outputs overlaying detected cysts on the original OCT images for easier interpretation.
Modular and Extensible: Code is organized in a way that allows customization and integration with more advanced deep learning models if needed.
Requirements
Python 3.x
Jupyter Notebook
Common libraries such as numpy, opencv-python, matplotlib, and scikit-image
You can install the dependencies using:
pip install -r requirements.txt
Usage
Clone this repository:
git clone <repository_url>
cd <repository_name>
Launch the Jupyter Notebook:
jupyter notebook
Open the provided notebook and follow the instructions to load your OCT dataset and run the cyst detection pipeline.
Notes
This notebook is intended for research and educational purposes and is not a substitute for professional medical diagnosis.
Accuracy depends on image quality and preprocessing parameters; further tuning may be required for different datasets.
