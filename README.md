SMART Goals Generation Project -Scripts for SMART Goals generation dissertation at Northeastern University -London

This repository contains the notebooks and files for a pipeline designed to generate SMART goals from vague input goals. The project leverages GPT-based methods fro building a dataset and T5 models for experimentation, fine-tuning, and evaluation.

Overview
The project aims to:

Develop a pipeline for generating SMART goals from vague inputs.
Experiment with data augmentation, cleaning, and multiple T5 model setups.
Evaluate and visualize results to identify the most effective techniques for SMART goal generation.

Pipeline Overview
The project is organized into sequential notebooks, each performing a specific task in the pipeline:

1_Goal_Generation.ipynb: Generates vague goals and their corresponding SMART goals using GPT-based methods.

2_Test_NLP_Techniques_Data_Augmentation.ipynb: Evaluates various NLP-based augmentation methods like back-translation and simplification.

3_Final_Augmentation.ipynb: Applies the selected data augmentation techniques to the dataset.

4_Data_Cleaning.ipynb: Cleans and preprocesses the augmented dataset, ensuring consistency and removing invalid entries.

5a_T5_Base_Experiment.ipynb: Evaluates the T5-Small model without fine-tuning as a baseline.

5b_T5_Small_and_Test_Deployment.ipynb: Runs experiments on T5-Small and includes the test deployment dataset.

5c_T5_LoRA_and_Beam_Search_Experiment.ipynb: Combines fine-tuning with LoRA and Beam Search decoding.

6_Visualization_and_Analysis.ipynb: Visualizes results and compares model performance across evaluation metrics.

How to Navigate

Follow the Notebooks in Order: Begin with 1_Goal_Generation.ipynb and proceed sequentially.

 Each notebook contains markdown cells explaining its purpose and outputs.

The full dataset is not included as instructed the code has been run.

Setup Requirements
To replicate the pipeline, you’ll need:
Python 3.8+: Ensure your environment is set up with a compatible Python version.
Google Colab: All notebooks were created and tested in Google Colab.




