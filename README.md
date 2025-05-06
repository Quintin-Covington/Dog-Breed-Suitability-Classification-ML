# Dog Breed Suitability Classification Based on Family Lifestyles

## Project Overview
This machine learning project classifies dog breeds into optimal categories based on key characteristics (energy level, friendliness, trainability, grooming needs, etc.). The model helps match prospective dog owners with breeds that best fit their lifestyle, improving compatibility and reducing pet abandonment rates.

Our solution is targeted toward:
- Pet adoption agencies
- Breeders
- Pet supply companies aiming to recommend ideal breeds to customers

## Skills and Techniques Used
- R Programming (Data Processing, ML Modeling)
- Exploratory Data Analysis (EDA)
- Clustering Analysis
- Supervised Machine Learning:
  - Random Forest Classifier
  - Support Vector Machine (SVM)
- Correlation Matrix Analysis
- Model Evaluation Metrics (Accuracy, Confusion Matrix)

## Dataset Attributes
- Breed name
- Energy Level
- Friendliness to Children
- Trainability
- Grooming Requirements
- Barking Level
- Adaptability to Living Spaces

## Methodology
- **Exploratory Data Analysis:** Cluster plots, correlation matrices to find natural breed groupings.
- **Modeling:** 
  - Random Forest classification model to predict breed suitability based on owner lifestyle categories.
  - Support Vector Machine (SVM) model to validate prediction robustness.
- **Feature Engineering:** Simplified and recoded breed characteristics for improved model performance.
- **Evaluation:** Accuracy and confusion matrices for model validation.

## Key Findings
- **Active families** (outdoor lifestyle) are best matched with Sporting dogs, Hounds, and Working breeds.
- **Busy families** and **single professionals** are better suited for Companion breeds and low-energy mixes.
- **Home-based families** with young children and **retired couples** align best with Hounds, Working dogs, and specific Sporting breeds.
- Breed recommendations can be fine-tuned based on factors like grooming effort, temperament, and exercise needs.

## Visuals
- Cluster plot for breed groupings
- Correlation matrix heatmaps
- Random Forest and SVM confusion matrices
- Decision trees for active vs. passive family recommendations

(*Visuals can be found in the HTML output or slides.*)

## How to Run
1. Open the `Final-IST-707-Group-Project.Rmd` file in RStudio.
2. Knit the file to generate an updated `.html` report if needed.
3. Alternatively, view the pre-generated `Final-IST-707-Group-Project.html` for full results without re-running.

Required R packages:  
- `tidyverse`
- `caret`
- `randomForest`
- `e1071`
- `ggplot2`

## Business Application
This model can help adoption centers and retailers:
- Make smarter breed-owner matches.
- Reduce return rates and pet rehoming.
- Boost customer satisfaction and loyalty.

## About Me
I'm Quintin Covington, a Data Scientist passionate about applying machine learning to solve real-world problems and improve community outcomes.

📫 Contact:  
- Email: Quintin.Covington@gmail.com

---
