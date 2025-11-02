# Improving Predictive Reliability and Automation of Smart Grids Using the StarNet Ensemble Model ⚡

> **Enhancing Predictive Reliability and Automation for Smart Grids with Machine Learning**

---

## 📝 Overview

**StarNet Ensemble** introduces a framework featuring an integrated machine-learning-driven GUI for predicting smart grid stability. This system leverages a stacking-based ensemble learning approach to ensure reliable and effective electricity distribution in smart grids.

---

## 🧑‍🔬 Abstract

The increasing complexity of modern power networks demands advanced predictive models to ensure grid stability and
autonomous operation. The purpose of this research is to improve the predictive reliability and automation of smart grids
through the development of the StarNet Ensemble Model, a stacking-based machine learning framework designed to enhance
stability forecasting and decision-making in dynamic energy environments. The proposed method integrates multiple base
learners in a hierarchical ensemble structure, enabling robust analysis and comparison across predictive models. A synthetic
dataset was generated from a 4-node star network and extended to include consumer node variations, comprising 60,000
data points with 12 predictive features and two dependent variables representing system stability states. Parameters such
as reaction times, nominal power values, and price elasticity coefficients were analyzed to train and validate the model.
Experimental evaluation demonstrates that the StarNet Ensemble Model achieved a prediction accuracy of 99.43%, significantly
outperforming conventional baseline models. The model enables real-time stability prediction and supports automated decision-
making for load management, demand response, and fault prevention. The findings reveal that the StarNet Ensemble Model
provides a scalable and intelligent solution for predictive maintenance and autonomous control in smart grids. Its high accuracy
and automation capability contribute to enhanced grid resilience, reduced operational costs, and improved reliability of future
energy systems.

---

## 📁 Repository Structure

```
Dataset/    # Synthetic smart grid datasets
Code/       # Source code, notebooks, and web-based GUI
```

---

## 🚀 Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/StarNet-Ensemble.git
   cd StarNet-Ensemble
   ```

2. **Install dependencies**
   ```bash
   # Example for Python projects
   pip install -r Code/requirements.txt
   ```

3. **Run the provided Jupyter notebook**
   - Open `Code/smart-grid-research-paper.ipynb` in Jupyter Notebook, JupyterLab, or VS Code.
   - **Update the dataset path** in the notebook to point to your local copy of the dataset (e.g., replace `/kaggle/input/smart-grid-stability/smart_grid_stability_augmented.csv` with the correct path).
   - Run all cells sequentially to reproduce the results and figures.

   ```bash
   # Example: launch Jupyter in the Code directory
   cd Code
   jupyter notebook
   ```

---

## 📊 Dataset Description

- **Source:** Synthetic, generated from a 4-node star network with consumer node variations.
- **Size:** 60,000 samples
- **Features:** 12 main predictive features (e.g., reaction times, nominal power, price elasticity)
- **Targets:** 2 dependent variables (system stability status)
- **Purpose:** Supports predictive modeling and evaluation within the web-based framework.

---

## 🏆 Results Summary

- **StarNet stacking ensemble model** achieved:
  - **Accuracy:** 99.43%
  - **Robustness:** Outperformed traditional and advanced ML models
- **Key Advantages:**
  - Real-time, web-based monitoring and prediction
  - Automated grid services (load shedding, demand response)
  - Predictive maintenance and reduced operational costs
  - Interactive GUI for stakeholders

---

## 👥 Authors

| Name                | Affiliation                                                                 | Email                               |
|---------------------|-----------------------------------------------------------------------------|-------------------------------------|
| Amit Chhabra<sup>†</sup><sup>‡</sup>        | CSE, Chandigarh College of Engineering and Technology, Chandigarh           | [amitchhabra@ccet.ac.in](mailto:amitchhabra@ccet.ac.in) |
| Sunil K. Singh<sup>‡</sup>      | CSE, Chandigarh College of Engineering and Technology, Chandigarh           | [sksingh@ccet.ac.in](mailto:sksingh@ccet.ac.in)         |
| Sudhakar Kumar<sup>‡</sup>      | CSE, Chandigarh College of Engineering and Technology, Chandigarh           | [sudhakar@ccet.ac.in](mailto:sudhakar@ccet.ac.in)       |
| Manraj Singh<sup>‡</sup>        | CSE, Chandigarh College of Engineering and Technology, Chandigarh           | [mannmanraj239@gmail.com](mailto:mannmanraj239@gmail.com) |
| Utkarsh Chauhan<sup>‡</sup>     | CSE, Chandigarh College of Engineering and Technology, Chandigarh           | [co21364@ccet.ac.in](mailto:co21364@ccet.ac.in)         |
| Saksham Arora<sup>‡</sup>       | CSE, Chandigarh College of Engineering and Technology, Chandigarh           | [mco22390@ccet.ac.in](mailto:mco22390@ccet.ac.in)       |
| Brij B. Gupta<sup>*</sup>       | Dept. of Computer Science & Info. Engg., Asia University, Taiwan            | [bbgupta@asia.eu.tw](mailto:bbgupta@asia.eu.tw)         |
| Wadee Alhalabi      | Dept. of Computer Science, King Abdulaziz University, Saudi Arabia          | [wsalhalabi@kau.edu.sa](mailto:wsalhalabi@kau.edu.sa)   |
| Varsha Arya         | Dept. of Business Administration, Asia University, Taiwan                   | [varshaarya2108@gmail.com](mailto:varshaarya2108@gmail.com) |
| Bassma Saleh Alsulami      | Dept. of Computer Science, King Abdulaziz University, Saudi Arabia          | [balsulami@kau.edu.sa](mailto:balsulami@kau.edu.sa)   |
| Ching-Hsien Hsu      | Dept. of Computer Science & Info. Engg., Asia University, Taiwan            | [robertchh@asia.edu.tw](mailto:robertchh@asia.edu.tw)         |
<sup>†</sup> Corresponding author <sup>‡</sup> Equal contribution <sup>*</sup> Principal Investigator

---

## 📚 Citation

> **Note:** This paper is currently **unpublished** and subject to change.  
> Please contact the authors before citing or referencing this work.

---

## 📬 Contact

For questions or collaboration, please contact the corresponding author:  
**Dr. Sudhakar Kumar** – [sudhakar@ccet.ac.in](mailto:sudhakar@ccet.ac.in)

---

## 📝 License

This project is licensed under the MIT License.  
See [LICENSE](LICENSE) for details.

---
